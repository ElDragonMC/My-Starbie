# My Starbie
This is my version of the Hack Club starbie

I liked and i wanted to make this project becouse it implies a PCB (i like designing them, sometimes i design ramdom things to spend some time) but i don't know how to code on arduino so i did not costumize the code a lot, only the main character). I loved to design and make this PCB, i've never thinked i could make a "tamagotchi" but i loved this.

# PCB Schematic
<img width="1169.5" height="827" alt="Schematic (3)-1" src="https://github.com/user-attachments/assets/ac5b4066-1ba1-473b-aca5-cab71a271812" />
<img width="620.5" height="424" alt="image" src="https://github.com/user-attachments/assets/62260c58-8fe6-4930-829a-4600b18b4878" />

# Some PCB Renders:

Front:
<img width="4288" height="2296" alt="StarbiePCB_Front" src="https://github.com/user-attachments/assets/1a341484-8267-4665-8d60-a3e0daf43793" />

Back:
<img width="4288" height="2296" alt="StarbiePCB_Back" src="https://github.com/user-attachments/assets/45fcf730-8296-4f51-894e-3a17bc37d43a" />

# Bill Of Materials

| Part | What it's for | Qty | Unit | Total | Vendor |
| --- | --- | --- | --- | --- | --- |
| [XIAO ESP32-C3](https://es.aliexpress.com/item/1005012304656509.html?spm=a2g0o.productlist.main.52.393c50213aHrDF&algo_pvid=25e16135-014c-45bc-8175-bd924d197a61&algo_exp_id=25e16135-014c-45bc-8175-bd924d197a61-49&pdp_ext_f=%7B%22order%22%3A%2261%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21EUR%219.35%219.49%21%21%2168.72%2169.77%21%40210381f017913975987262614e0e1f%2112000058028048245%21sea%21ES%210%21ABX%211%210%21n_tag%3A-29910%3Bd%3A2404ebf5%3Bm03_new_user%3A-29895&curPageLogUid=JLlfsNJBviBG&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005012304656509%7C_p_origin_prod%3A) | Main Processor | 1 | $10.63 | $10.63 | [Aliexpress ES](https://es.aliexpress.com/item/1005012304656509.html?spm=a2g0o.productlist.main.52.393c50213aHrDF&algo_pvid=25e16135-014c-45bc-8175-bd924d197a61&algo_exp_id=25e16135-014c-45bc-8175-bd924d197a61-49&pdp_ext_f=%7B%22order%22%3A%2261%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21EUR%219.35%219.49%21%21%2168.72%2169.77%21%40210381f017913975987262614e0e1f%2112000058028048245%21sea%21ES%210%21ABX%211%210%21n_tag%3A-29910%3Bd%3A2404ebf5%3Bm03_new_user%3A-29895&curPageLogUid=JLlfsNJBviBG&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005012304656509%7C_p_origin_prod%3A) |
| [x10 Switches](https://es.aliexpress.com/item/1005004341695529.html?spm=a2g0o.productlist.main.22.5ab61b6eVVnSu6&algo_pvid=65f13a5c-e468-4d1d-b142-602fbbe4cb01&algo_exp_id=65f13a5c-e468-4d1d-b142-602fbbe4cb01-21&pdp_ext_f=%7B%22order%22%3A%222106%22%2C%22spu_best_type%22%3A%22price%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21EUR%212.53%212.53%21%21%2118.61%2118.61%21%402161390417917200379237824e0e2b%2112000028826681974%21sea%21ES%214844224188%21ACX%211%210%21n_tag%3A-29919%3Bd%3A6e95c66c%3Bm03_new_user%3A-29894&curPageLogUid=4IWCT3EQSZya&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005004341695529%7C_p_origin_prod%3A) | Buttons | 1 | $2.83 | $2.83 | [Aliexpress ES](https://es.aliexpress.com/item/1005004341695529.html?spm=a2g0o.productlist.main.22.5ab61b6eVVnSu6&algo_pvid=65f13a5c-e468-4d1d-b142-602fbbe4cb01&algo_exp_id=65f13a5c-e468-4d1d-b142-602fbbe4cb01-21&pdp_ext_f=%7B%22order%22%3A%222106%22%2C%22spu_best_type%22%3A%22price%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21EUR%212.53%212.53%21%21%2118.61%2118.61%21%402161390417917200379237824e0e2b%2112000028826681974%21sea%21ES%214844224188%21ACX%211%210%21n_tag%3A-29919%3Bd%3A6e95c66c%3Bm03_new_user%3A-29894&curPageLogUid=4IWCT3EQSZya&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005004341695529%7C_p_origin_prod%3A) |
| [OLED](https://es.aliexpress.com/item/1005006262908701.html?spm=a2g0o.productlist.main.9.4a077542JsKpZa&algo_pvid=30ecde4d-b5cc-4c22-85f1-04b446f32617&algo_exp_id=30ecde4d-b5cc-4c22-85f1-04b446f32617-8&pdp_ext_f=%7B%22order%22%3A%2214148%22%2C%22spu_best_type%22%3A%22price%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21EUR%212.09%212.09%21%21%2115.37%2115.35%21%400b884b5817917199391296995e10a5%2112000036518346431%21sea%21ES%214844224188%21ACX%211%210%21n_tag%3A-29919%3Bd%3A6e95c66c%3Bm03_new_user%3A-29894&curPageLogUid=FBYpUQKB9djJ&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005006262908701%7C_p_origin_prod%3A) | Main Screen | 1 | $2.34 | $2.34 | [Aliexpress ES](https://es.aliexpress.com/item/1005006262908701.html?spm=a2g0o.productlist.main.9.4a077542JsKpZa&algo_pvid=30ecde4d-b5cc-4c22-85f1-04b446f32617&algo_exp_id=30ecde4d-b5cc-4c22-85f1-04b446f32617-8&pdp_ext_f=%7B%22order%22%3A%2214148%22%2C%22spu_best_type%22%3A%22price%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21EUR%212.09%212.09%21%21%2115.37%2115.35%21%400b884b5817917199391296995e10a5%2112000036518346431%21sea%21ES%214844224188%21ACX%211%210%21n_tag%3A-29919%3Bd%3A6e95c66c%3Bm03_new_user%3A-29894&curPageLogUid=FBYpUQKB9djJ&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005006262908701%7C_p_origin_prod%3A) |
| [Aosong DHT11](https://es.aliexpress.com/item/1005009073170322.html?spm=a2g0o.productlist.main.2.1faa48470t0JQd&algo_pvid=e6979c1e-7e1b-4707-94da-2db0aba38971&algo_exp_id=e6979c1e-7e1b-4707-94da-2db0aba38971-1&pdp_ext_f=%7B%22order%22%3A%22467%22%2C%22spu_best_type%22%3A%22price%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21EUR%210.88%210.91%21%21%210.97%211.00%21%400b0fe0e117913969556701941e0f76%2112000047819045373%21sea%21ES%210%21ABX%211%210%21n_tag%3A-29910%3Bd%3A2404ebf5%3Bm03_new_user%3A-29895&curPageLogUid=MtLNhRqEcWq7&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005009073170322%7C_p_origin_prod%3A) | Ambient sensor | 1 | $1.02 | $1.02 | [Aliexpress ES](https://es.aliexpress.com/item/1005009073170322.html?spm=a2g0o.productlist.main.2.1faa48470t0JQd&algo_pvid=e6979c1e-7e1b-4707-94da-2db0aba38971&algo_exp_id=e6979c1e-7e1b-4707-94da-2db0aba38971-1&pdp_ext_f=%7B%22order%22%3A%22467%22%2C%22spu_best_type%22%3A%22price%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21EUR%210.88%210.91%21%21%210.97%211.00%21%400b0fe0e117913969556701941e0f76%2112000047819045373%21sea%21ES%210%21ABX%211%210%21n_tag%3A-29910%3Bd%3A2404ebf5%3Bm03_new_user%3A-29895&curPageLogUid=MtLNhRqEcWq7&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005009073170322%7C_p_origin_prod%3A) |
| [x50 Resistors](https://es.aliexpress.com/item/1005009330094258.html?spm=a2g0o.detail.0.0.111coYGJoYGJeJ&mp=1&pdp_npi=6%40dis%21EUR%21EUR+1.37%21EUR+1.28%21%21EUR+1.28%21%21%21%400b884a9917917201687254315e0fb7%2112000048778024089%21ct%21ES%214844224188%21%211%210%21&pdp_ext_f=%7B%22cart2PdpParams%22%3A%7B%22pdpBusinessMode%22%3A%22retail%22%7D%7D&gatewayAdapt=glo2esp) | Resistance | 1 | $1.43 | $1.43 | [Aliexpress ES](https://es.aliexpress.com/item/1005009330094258.html?spm=a2g0o.detail.0.0.111coYGJoYGJeJ&mp=1&pdp_npi=6%40dis%21EUR%21EUR+1.37%21EUR+1.28%21%21EUR+1.28%21%21%21%400b884a9917917201687254315e0fb7%2112000048778024089%21ct%21ES%214844224188%21%211%210%21&pdp_ext_f=%7B%22cart2PdpParams%22%3A%7B%22pdpBusinessMode%22%3A%22retail%22%7D%7D&gatewayAdapt=glo2esp) |
| [MPU6050](https://es.aliexpress.com/item/1005010057794277.html?spm=a2g0o.productlist.main.2.4214742ckjfBDd&algo_pvid=1a523da7-b516-4c7a-b534-591b4346eeca&algo_exp_id=1a523da7-b516-4c7a-b534-591b4346eeca-1&pdp_ext_f=%7B%22order%22%3A%223439%22%2C%22spu_best_type%22%3A%22price%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21EUR%211.85%211.85%21%21%212.03%212.03%21%400b15831117917202748735141e0e72%2112000050979433010%21sea%21ES%214844224188%21ACX%211%210%21n_tag%3A-29919%3Bd%3A6e95c66c%3Bm03_new_user%3A-29894&curPageLogUid=609FsAH3uwv2&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005010057794277%7C_p_origin_prod%3A) | Rotation and Velocity sensor | 1 | $2.07 | $2.07 | [Aliexpress ES](https://es.aliexpress.com/item/1005010057794277.html?spm=a2g0o.productlist.main.2.4214742ckjfBDd&algo_pvid=1a523da7-b516-4c7a-b534-591b4346eeca&algo_exp_id=1a523da7-b516-4c7a-b534-591b4346eeca-1&pdp_ext_f=%7B%22order%22%3A%223439%22%2C%22spu_best_type%22%3A%22price%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21EUR%211.85%211.85%21%21%212.03%212.03%21%400b15831117917202748735141e0e72%2112000050979433010%21sea%21ES%214844224188%21ACX%211%210%21n_tag%3A-29919%3Bd%3A6e95c66c%3Bm03_new_user%3A-29894&curPageLogUid=609FsAH3uwv2&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005010057794277%7C_p_origin_prod%3A) |
| [PCB](https://jlcpcb.com) | Main circuit (it's so cheap beacouse i used a 10$ coupon) | 1 | $1.95 | $1.95 | [JLCPCB](https://jlcpcb.com) |
| **Parts subtotal** | — | — | — | **$22.27** | — |
| **Tax & shipping** | — | — | — | **$0.00** | — |
| **Total** | — | — | — | **$22.27** | — |

# Desing Process

I designed the PCB with KiCad (the only PCB design software i know to use) following the guide from HackClub. The code i've grabbed it from the guide and i changed the main character to a yoda. <img width="32" height="32" alt="oled_art" src="https://github.com/user-attachments/assets/337f1b50-c56c-4418-9f9c-4513e987ae4b" />
I waned to design a case for this project but i did not have that much time left and also i think the sleek black PCB will look very cool.

# How to assemble

1. First grab the PCB and verify if it's cleen and well-made.
2. Grab the ESP32, the screen and the motion sensor and weld the headers. For the ESP32, two 7 pin header, for the motion sensor, a 8 pin header and the screen a 4 pin header.
3. Weld the ESP32, the screen, the motion sensor, the DHT sensor, the resistance and the two switches to the PCB.
4. Print and put the [keycaps](https://github.com/ElDragonMC/My-Starbie/blob/c5b6d291949e9c5069404fdc13d41a3a265bef9a/keycap.stl).

# How to upload the firmware

1. Open the Arduino IDE
2. Open **File → Preferences**. In **Additional Boards Manager URLs**, add:

   ~~~text
   https://espressif.github.io/arduino-esp32/package_esp32_index.json
   ~~~

3. Open **Tools → Board → Boards Manager**, search for esp32, and install **esp32 by Espressif Systems**.
4. Under **Tools → Board → esp32**, select **XIAO_ESP32C3**.
5. Open **Sketch → Include Library → Manage Libraries**. Install these libraries one at a time:

   - Adafruit GFX Library
   - Adafruit SSD1306
   - Adafruit MPU6050
   - DHT sensor library

   If Arduino asks to install dependencies, choose **Install All**.

6. Connect the ESP32 to the computer.
7. Open Starbie.ino and click Arduino's arrow-shaped **Upload** button to upload the firmware to the board.

# Controls

| Control | What it does |
| --- | --- |
| Button 1, first press | Opens the radial menu |
| Tilt while menu is open | Moves the selector ball; each general direction is one large sector |
| Button 1, second press | Chooses the highlighted action |
| Button 2 | Shows or hides the stats screen |
| Shake while seeing the pet | Gives Yoda its shake reaction |

# Some ideas i had:

- Add some AAA bateries to power the ESP32 but i would be over budget
- Put more options on the menu but i don't know how to code on arduino and the week is over
- With the ESP32, connect it to a phone through bluetooth so i can get some notifications like feed me or something else but as i said i don't know how to do it
- Put a speaker but it would be over budget and also i don't know how to program on arduino

# Update!!

I could reduce the PCB price with a coupon so i could put some batteries but i don't have enough time
