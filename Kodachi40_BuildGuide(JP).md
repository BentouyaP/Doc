# Kodachi40 BuildGuide

# Parts List

 [PCB Garber](https://github.com/BentouyaP/Gerber/tree/master/Kodachi40) / [Acrylic Case](https://github.com/BentouyaP/KeyboardCase/tree/master/Kodachi40)  

    Kodachi40 PCB                                                               1個     
    Mtmega32U4 Promicro 5V/16MHz                                                1個
    1N4148 スイッチングダイオード, SOD-123 package or DO-35 (0.3" pitch)         44個
    Cherry MX switches, PCB or plate-mounted                                   44個
    Cherry Stabilizer 2U                                                        2個
    ANSI KeyCap Set (104keys)                                                1セット
    Case                                                                      1台分
    Screw & Nuts 3M                                                             9本
    LED Strip (Optional)                                                        1枚

# The Build Process /ここから日本語
※画像や詳細説明は都度追加予定

1.PCBにスイッチングダイオードをはんだ付け

    ホールが四角(■)の端子と丸(●)の端子がありますが、四角い端子へカソード(-)を向けてください。
    
    ※カソード＝黒いラインが入っている方

2.PCBにPromicroピンをはんだづけ

3.PCB/プレートにStabilizerを2つ取り付け

4.プレートにCherryMXスイッチ取り付け

    Promicroが重なる2つのキー(Aキー＋左隣の1.25uキー)は、スイッチピンがPCBから飛び出してPromicroに接触する恐れがあります。
    そのため事前に飛び出た部分をニッパーなどで切断しておくことをオススメします。
    なおアクリルプレートの場合、スタビライザー部分の2キーはPCBマウントになります。

5.PCBとプレートを重ね、CherryMxスイッチを装着

6.PCBにCherryMxスイッチをはんだ付け

7.スタビライザーの2キーを装着、はんだ付け

    ５PinのCherryMXスイッチだと安定します。

8.PCBにPrimicroをはんだ付け

    向きに注意してください。チップが見える面をPCB側へ向けてください。
    ショート対策としてビニールテープでPromicro表面を絶縁することをオススメします。

9.(Option)PCBにLED Stripをはんだ付け

10.ケース組み立て

11.キーキャップ取り付け

12.完成

