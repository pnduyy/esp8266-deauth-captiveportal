# esp8266-captive_portal_pnd from:
https://github.com/adamff1/ESP8266-Captive-Portal
  - Open your Arduino IDE and go to "File -> Preferences -> Boards Manager URLs" and paste the following link: http://arduino.esp8266.com/stable/package_esp8266com_index.json
  - Go to "Tools -> Board -> Boards Manager", search "esp8266" and install esp8266
# esp8266-deauther from:
https://github.com/SpacehuhnTech/esp8266_deauther

---------------------------------------------------
Wifi mặc định của esp8266_captive_portal_pnd là "__hihi__", IP="172.0.0.1"
Wifi mặc định của esp8266_deauther_pnd là "__hihi__", pass="09876543", IP="192.168.4.1"

#esp8266-captive-portal-duy:
  + "172.0.0.1/index"
  + "172.0.0.1/mk" để xem mật khẩu đã lưu.
  + "172.0.0.1/wifi" để đổi tên wifi.
 Sau khi nhập mk wifi, esp8266-captive-portal-pnd sẽ reset lại tên wifi về mặc định và gửi 1 tín hiệu đến chân RST của esp8266_deauther_pnd để STOP deauth.

