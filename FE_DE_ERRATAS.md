# Fe de erratas

Estado a noviembre de 2026. Los simulacros proceden de **reconstrucciones de terceros** (no son
cuadernillos publicados por la JLPT), así que heredan sus lagunas. Este documento recoge lo que se
sabe que falta o que se corrigió, para que puedas confiar en el resto.

Cada pregunta tiene un identificador `AAAA-MM_SN_NN`: examen, sección (V vocabulario, G gramática,
R lectura, L listening), número de 問題 y número de pregunta. Por ejemplo, `2015-07_G3_23` es
la pregunta 23 de 文法 問題3 de julio de 2015. En el banco CSV la columna `revisar` trae además
las notas de cada pregunta (incluidas las 506 erratas corregidas cotejando con la edición escaneada).

## 1. Lagunas de las fuentes

Lo que no está en ninguna de las fuentes disponibles y, por tanto, tampoco en el simulacro.

| Examen | Sección | Qué falta o qué es distinto |
|---|---|---|
| 2010-12 | 文字・語彙, 文法, 読解 | No se conserva el cuadernillo: solo hay listening. |
| 2010-12 | 聴解 問題1 y 2 | Faltan las opciones impresas; el guion y la clave sí están. |
| 2011-07 | 聴解 問題5 | Trae 8 ítems de 即時応答 en lugar de 9. |
| 2011-12 | 聴解 問題5 | Trae 8 ítems de 即時応答 en lugar de 9. |
| 2013-12 | 聴解 問題5 6番 | La fuente repite por error las opciones de 5番; se imprime sin opciones. La clave sí consta. |
| 2022-07 | 文字・語彙 | 34 preguntas: falta una de 漢字読み. |
| 2022-07 | 読解 問題7 | Solo una pregunta (impresa como 38 en la fuente). |
| 2024-07 | 読解 問題4 (24) | La opción 4 viene de otra pregunta en las dos ediciones; la respuesta correcta (3) no cambia. |
| 2024-12 | 聴解 | Todavía no hay audio; el cuadernillo, el guion y la clave sí están. |

Desde diciembre de 2020, 文法 問題3 tiene 4 preguntas (19-22) y la lectura va del 23 al 38: no es
una errata, es el formato vigente.

## 2. Correcciones hechas a mano sobre la fuente

Decisiones tomadas leyendo la pregunta, el dibujo, la tabla de respuestas o una tercera fuente.
Donde dos fuentes daban claves distintas, se decidió por el contenido.

| Examen | Sección | N.º | Id | Cambio | Motivo |
|---|---|---|---|---|---|
| 2010-07 | 聴解 問題1 | 1 | `2010-07_L1_01` | Clave: **1** | guion=3 y tabla=1: el diálogo pide cuello abierto y no negro → dibujo 1 (blanco, cuello abierto) |
| 2010-07 | 読解 問題7 | 39 | `2010-07_R7_39` | Opciones: （はがき１） / （はがき２） / （はがき３） / （はがき４）; Enunciado reconstruido | las opciones son cuatro dibujos de postales (ver imagen del folleto) |
| 2011-07 | 文法 問題3 | 23 | `2011-07_G3_23` | Opciones: なるのでしょうか / なったでしょう / なってしまうのです / なってしまいました | la fuente imprime «3» en lugar de «4» y las opciones 3 y 4 venían pegadas |
| 2011-12 | 文法 問題1 | 2 | `2011-12_G1_02` | Comprobado, sin cambios | la fuente numera mal los marcadores de opción; opciones の・も・を・で comprobadas, clave 3 (丸い形をしている) |
| 2013-07 | 聴解 問題1 | 6 | `2013-07_L1_06` | Clave: **1** | guion=1 y tabla=4: lo primero es asistir al 説明会, que empieza ya |
| 2013-12 | 聴解 問題5 | 6 | `2013-12_L5_06` | Opciones: sin opciones (no constan en ninguna fuente) | la fuente repite por error las opciones de 5番; las opciones reales no están en ninguna fuente (respuesta según la tabla) |
| 2013-12 | 読解 問題7 | 39 | `2013-12_R7_39` | Opciones: ① / ② / ③ / ④ | opciones en dos columnas; el folleto se había pegado a la opción 4 |
| 2015-07 | 文法 問題3 | 23 | `2015-07_G3_23` | Opciones: 大好きな言葉があります / 私が大好きな言葉です / 大好きだという点です / 大好きそうな点です | la fuente imprime «3» en lugar de «4» y las opciones 3 y 4 venían pegadas |
| 2015-07 | 聴解 問題1 | 5 | `2015-07_L1_05` | Clave: **2** | guion=2 y tabla=1: al terminar la clase van directo al 講演会 |
| 2015-12 | 文字・語彙 問題3 | 18 | `2015-12_V3_18` | Clave: **1**; Opciones: 戦う / 踏む / 壊す / 曲げる | la reconstrucción traía 挑む y clave 3; la explicación de 日语轻松考 da 1 戦う / 2 踏む / 3 壊す / 4 曲げる con 正解 1 (下一场比赛的竞争对手是去年的冠军) |
| 2016-07 | 文法 問題1 | 10 | `2016-07_G1_10` | Opciones: ことにするのは / ことができるのは / ことにするまで / ことができるまで | la fuente imprime «3» en lugar de «2» y las cuatro opciones venían pegadas |
| 2016-07 | 文法 問題3 | 21 | `2016-07_G3_21` | Opciones: 言いました / 言ってもらえました / 言わせました / 言わされました | la fuente imprime «3» en lugar de «2» y las cuatro opciones venían pegadas |
| 2017-07 | 文法 問題3 | 23 | `2017-07_G3_23` | Opciones: 身についてもいいです / 身についていいだけです / 身についていいと思います / 身についてもいいと思うだけです | la fuente imprime «3» en lugar de «4» y las opciones 3 y 4 venían pegadas |
| 2018-12 | 文字・語彙 問題1 | 7 | `2018-12_V1_07` | Enunciado reconstruido | subrayado perdido en el PDF texto |
| 2018-12 | 文字・語彙 問題1 | 8 | `2018-12_V1_08` | Enunciado reconstruido | subrayado perdido en el PDF texto |
| 2018-12 | 聴解 問題1 | 2 | `2018-12_L1_02` | Clave: **4** | guion=2 y tabla=4: él llama a la tienda de bentō; la sala la cambia ella |
| 2020-12 | 文法 問題2 | 15 | `2020-12_G2_15` | Enunciado reconstruido | huecos del ★ reconstruidos: はじまる まで あと3分 しかない |
| 2020-12 | 文法 問題2 | 16 | `2020-12_G2_16` | Enunciado reconstruido | huecos del ★ reconstruidos: 晴れる と いい の |
| 2021-07 | 文字・語彙 問題1 | 4 | `2021-07_V1_04` | Opciones: しゅしゃ / しゅうしゃ / ちゅしゃ / ちゅうしゃ; Enunciado reconstruido | opciones con や grande y しましよう en el PDF texto; cotejado con el escaneo |
| 2022-07 | 文法 問題2 | 14 | `2022-07_G2_14` | Enunciado reconstruido | huecos del ★ reconstruidos: あの 先生ほど わかりやすく教えてくれる 先生は |
| 2022-07 | 読解 問題7 | 37 | `2022-07_R7_37` | Comprobado, sin cambios | la reconstrucción solo trae esta pregunta de 問題7 (impresa como 38); clave 2 comprobada con el folleto: el pago es el mismo día y la guitarra es opcional |
| 2022-12 | 文法 問題1 | 11 | `2022-12_G1_11` | Clave: **2** | 沪江=1 y Dungmori=2: 中川がおりますので (humilde) |
| 2022-12 | 文法 問題3 | 22 | `2022-12_G3_22` | Clave: **2** | 沪江=3 y Dungmori=2: conclusión personal → なるのだと感じました |
| 2022-12 | 聴解 問題1 | 2 | `2022-12_L1_02` | Clave: **2** | guion/Dungmori=1 y 沪江=2: debe enviar el documento por correo; imprimir no hace falta |
| 2023-07 | 読解 問題7 | 37 | `2023-07_R7_37` | Opciones: ①と②と③ / ①と② / ③と④ / ③ | la fuente imprime «1» en lugar de «2» y las cuatro opciones venían pegadas |
| 2024-07 | 文法 問題2 | 18 | `2024-07_G2_18` | Enunciado reconstruido | huecos del ★ reconstruidos: 受付の林さん と 結婚するんだ って |
| 2024-07 | 読解 問題4 | 24 | `2024-07_R4_24` | Comprobado, sin cambios | la opción 4 de la reconstrucción viene de otra pregunta (igual en las dos ediciones); la respuesta 3 no cambia |
| 2024-12 | 文字・語彙 問題2 | 14 | `2024-12_V2_14` | Opciones: 違 / 変 / 逆 / 別 | las opciones traían 变 y 别 (formas chinas simplificadas de 変 y 別) |
| 2024-12 | 文法 問題2 | 18 | `2024-12_G2_18` | Enunciado reconstruido | huecos del ★ reconstruidos: だけではなく 大きな窓から海が見えて 景色を楽しみながら 読書ができるのも |

### Textos de lectura corregidos

| Examen | Pasaje | Corrección |
|---|---|---|
| 2011-12 | 読解 問題5 (2) | El subrayado ② empezaba antes de tiempo; ahora cubre solo «そうではない». |
| 2012-12 | 読解 問題6 | El subrayado ① empezaba a mitad de palabra; ahora cubre «多くの野菜を生産することができます». |
| 2021-07 | 読解 問題5 (1) | «子どものころの思い出と異なる» → «重なる», como en la edición escaneada. |
| 2022-07 | 読解 問題5 (1) | El subrayado ② venía partido en dos renglones; ahora es una sola unidad («困ったこと»). |
| 2022-07 | 読解 問題7 | Se quitó un renglón de otra pregunta que encabezaba el folleto («4 10,000円から…»). |

Además, en todas las secciones de 文字・語彙, 文法 y 読解 se cotejó el texto pregunta por pregunta
con la edición escaneada: 506 erratas corregidas (kanji equivocados, kana pequeño, dakuten,
subrayados mal puestos, opciones pegadas de otra pregunta, furigana incrustado). Cada una consta en
la columna `revisar` del banco CSV.

## 3. Dudas abiertas

Puntos en los que las fuentes no coinciden o el texto parece dudoso, pero que no afectan a la clave.
Se dejaron como en la fuente.

| Id | Observación |
|---|---|
| `2021-12_R5_29` | La opción 1 dice «生きる値段のある人間»; lo natural sería «価値». Las dos ediciones dicen 値段. Es un distractor. |
| `2021-07_V3_17` | La edición escaneada invierte el orden de las opciones 3 y 4. La clave corresponde al orden impreso aquí. |
| `2019-12_G1_06` | El orden de las opciones difiere entre ediciones. La clave corresponde al orden impreso aquí. |
| `2023-07_G2_14` | La edición escaneada coloca la ★ en otro hueco. Se mantiene la versión que coincide con la clave (2). |
| `2024-12_G3_19` | Según el escaneo, las opciones 2 y 3 van al revés. La clave (1) no cambia. |

## 4. Guiones y audio

- Los guiones de listening se transcribieron leyendo las páginas de las fuentes, porque en los PDF el
  diálogo es imagen. Coinciden en un 85-95 % con las transcripciones independientes que existen; las
  diferencias son de detalle (partículas, interjecciones), normales entre dos transcripciones del
  mismo audio.
- El audio es el de cada fuente, sin editar. 2010-12 viene en `.m4a`.

## 5. Dibujos

- Los dibujos son la página original recortada y pasada a escala de grises con el papel en blanco.
  En algunos queda un rastro gris muy tenue del logo de la academia (por ejemplo 2015-07, 2018-12 y
  2019-07 en 聴解 問題4, y 2024-12 en 聴解 問題1 3番): es del mismo gris que el dibujo y no se puede
  quitar sin dañarlo.
- Los dibujos que ya eran muy pequeños en la fuente (2024-12 聴解 問題1 3番, 2020-12 聴解 問題1 6番)
  se amplían hasta 2,5 veces; más allá se verían pixelados.
- Se eliminaron restos de las reconstrucciones que el cuadernillo oficial no tiene: números de opción
  duplicados («1 1  2 2…» en 2013-07, 2014-12, 2015-07 y 2017-07), filas «1 2 3 4» para contestar
  bajo dibujos que ya llevan su número, rejillas de respuesta bajo 問題4, etiquetas «N番»
  originales dentro de los recortes y la marca roja de respuesta que traía la hoja de 2024-07.

## Cómo informar de una errata nueva

Abre un *issue* con el identificador de la pregunta (por ejemplo `2015-07_G3_23`), qué dice el
simulacro y qué debería decir.
