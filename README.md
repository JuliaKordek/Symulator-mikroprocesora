# Symulator-mikroprocesora
Aplikacja stanowiącą model programowego symulatora mikroprocesora w języku C#. Aplikacja umożliwia wykonywanie trzech operacji: ADD, MOV, SUB na czterech 16- bitowych rejestrach AX, BX, CX, DX. Możliwość realizacji tych operacji w dwóch dostępnych trybach tj. w trybie krokowym oraz w trybie całościowego wykonania.
Interfejs został stworzony przy użyciu Windows Forms.
Składa się on z jednego okna głównego, które zawiera pola TexBox umożliwiające: wybór odpowiedniej operacji, podanie rejestru źródłowego i docelowego oraz wartości na jakiej ma zostać wykonana operacja, podgląd zawartości rejestrów AX-DX oraz listy wykonanych operacji w trybie krokowym lub wpisanych do wykonania w trybie całościowego wykonania.
Okno główne Form1 zawiera także przyciski Button do wykonywania operacji w trybie krokowym oraz rejestrowym, przycisk dodania operacji do listy w trybie całościowego wykonania oraz przycisk czyszczący okna TextBox.
