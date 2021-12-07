
[PRK Firmware Advent Calendar 2021](https://adventar.org/calendars/7086)  
キーマップを書くにあたってキーコードを一覧できるものが欲しくなったので作りました。0.9.7のものです。  
8日目が開いていたので、みなさん本格的な記事の中恐れ入りますが投稿いたします。

ちなみにCtrl+Zのような組み合わせのキーは適当な名前のキーコード（Z_LCTLなど）をキーマップに書いてしまった後に  
kbd.define_mode_key :ZLCTL,  [ :KC_Z, :KC_LCTL 150, 150 ]  
と定義するようです。宣言したりは要らないんですね！

KC_LCTL : 左CTRL  
KC_LSFT : 左SHIFT  
KC_LALT : 左ALT  
KC_LGUI : 左のWIN/CMD
KC_RCTL : 右CTRL  
KC_RSFT : 右SHIFT  
KC_RALT : 右ALT  
KC_RGUI : 右のWIN/CMD  
KC_NO : キー割り当てなし  
KC_A :   
KC_B :   
KC_C :   
KC_D :   
KC_E :   
KC_F :   
KC_G :   
KC_H :   
KC_I :   
KC_J :   
KC_K :   
KC_L :   
KC_M :   
KC_N :   
KC_O :   
KC_P :   
KC_Q :   
KC_R :   
KC_S :   
KC_T :   
KC_U :   
KC_V :   
KC_W :   
KC_X :   
KC_Y :   
KC_Z :   
KC_1 :   
KC_2 :   
KC_3 :   
KC_4 :   
KC_5 :   
KC_6 :   
KC_7 :   
KC_8 :   
KC_9 :   
KC_0 :   
KC_ENTER :   
KC_ESCAPE :   
KC_BSPACE :   
KC_TAB :   
KC_SPACE :   
KC_MINUS : -  
KC_EQUAL : =  
KC_LBRACKET : [  
KC_RBRACKET : ]  
KC_BSLASH : \|  
KC_NONUS_HASH : \~  
KC_SCOLON : ;  
KC_QUOTE : '  
KC_GRAVE : `  
KC_COMMA : ,  
KC_DOT : .  
KC_SLASH : /  
KC_CAPSLOCK :   
KC_F1 :   
KC_F2 :   
KC_F3 :   
KC_F4 :   
KC_F5 :   
KC_F6 :   
KC_F7 :   
KC_F8 :   
KC_F9 :   
KC_F10 :   
KC_F11 :   
KC_F12 :   
KC_PSCREEN : PrintScreen  
KC_SCROLLLOCK :   
KC_PAUSE :   
KC_INSERT :   
KC_HOME :   
KC_PGUP : PageUp  
KC_DELETE :   
KC_END :   
KC_PGDOWN : PageDown  
KC_RIGHT :   
KC_LEFT :   
KC_DOWN :   
KC_UP :   
KC_NUMLOCK :   
KC_KP_SLASH : /  
KC_KP_ASTERISK : *  
KC_KP_MINUS : -  
KC_KP_PLUS : +  
KC_KP_ENTER :   
KC_KP_1 :   
KC_KP_2 :   
KC_KP_3 :   
KC_KP_4 :   
KC_KP_5 :   
KC_KP_6 :   
KC_KP_7 :   
KC_KP_8 :   
KC_KP_9 :   
KC_KP_0 :   
KC_KP_DOT : .  
KC_NONUS_BSLASH : \|  
KC_APPLICATION : 右クリック  
KC_KP_EQUAL : =  
KC_F13 :   
KC_F14 :   
KC_F15 :   
KC_F16 :   
KC_F17 :   
KC_F18 :   
KC_F19 :   
KC_F20 :   
KC_F21 :   
KC_F22 :   
KC_F23 :   
KC_F24 :     
KC_LANG1 : かな  
KC_LANG2 : 英数  
KC_EXLM : !  
KC_AT : @  
KC_HASH : #  
KC_DLR : $  
KC_PERC : %  
KC_CIRC : ^  
KC_AMPR : &  
KC_ASTER : *  
KC_LPRN : (  
KC_RPRN : )  
KC_UNDS : _  
KC_PLUS : +  
KC_LCBR : {  
KC_RCBR : }  
KC_PIPE : |   
KC_COLON :  :  
KC_DQUO : "  
KC_TILD : ~  
KC_LABK : <  
KC_RABK : >  
KC_QUES : ?  
RGB_TOG : RGBオン/オフ  
RGB_MODE_FORWARD : 次の発光パターン  
RGB_MOD : 次の発光パターン  
RGB_MODE_REVERSE : 前の発光パターン
RGB_RMOD : 前の発光パターン   
RGB_HUI : 色相↑   
RGB_HUD : 色相↓  
RGB_SAI : 彩度↑  
RGB_SAD : 彩度↓  
RGB_VAI : 輝度↑  
RGB_VAD : 輝度↓  
RGB_SPI : 速度↑  
RGB_SPD : 速度↓  
