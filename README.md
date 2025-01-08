# Chapter_3_Platform_Competition
The following is written in Japanese:

DSとPSP間プラットフォーム競争モデル -> DS_PSP. WiiとPS3間プラットフォーム競争モデル -> Wii_PS3.

Vensim_Models -> 日本語で作成されたシステムダイナミクス（SD）モデルとデータ。Vensim_eModels -> 英語で作成されたシステムダイナミクス（SD）モデルとデータ。

Julia_Models -> Juliaコードで作成された動的モデルとデータ。実行結果の一般線形/非線形回帰モデル。等高線出力。

これらのモデルファイルを実行するためには有償版のVemsim ProfessionalあるいはVensom DSSが必要である。モデル内の変数と定数名は日本語で表記されている。

Vensimは、Version10以降、モデルの表記法を独自形式に変更した。従来のシステム・ダイナミクスの表記法に変更してモデルを表示するためには、以下の指定を行う。

［ビュー］アイコン→「伝統的なスケッチスタイル」を選択する。

WiiとPS3間プラットフォーム競争の動的モデル　

![Chapter_3_Fig_3_3](https://github.com/user-attachments/assets/0c9dd133-73fd-4b75-9de0-f684c4a41d99)
#
he x.mdl file is an SD model file for Ventana Systems Vensim. It utilizes Vemsim's subscript functionality for modeling two-sided markets.

To run these model files, you need the paid versions of Vemsim Professional or Vensom DSS. Variables and constant names in the models are written in English.

Vensim has changed the notation of models to its own format since Version 10. To change to the traditional system dynamics notation and display the model, specify the following

［Select the View icon -> “Traditional Sketch Style”.

DS and PSP inter-platform competition model -> DS_PSP_eModel

Wii and PS3 inter-platform competition model -> Wii_PS3_eModel

Service provider migration flag=0. Fixed to 1 units sold per user. Withdrawal action flag=0.

Model 0: Multiply the network effect coefficient by the intersection of the number of adopters on the other side and the change in the number of complements -> 0_DS_PSP_eModel.mdl, 0_Wii_PS3_eModel.mdl.

Model 1: Multiply the network effect coefficient only by the degree of change in the number of recruits on the other side (formulation of the cross-side network effect) -> 1_DS_PSP_eModel.mdl, 1_Wii_PS3_eModel.mdl.

Model 2: Multiply the network effect coefficient only by the degree of change in complements on the other side (formulation of indirect network effect)-> 2_DS_PSP_eModel.mdl, 2_Wii_PS3_eModel.mdl.
