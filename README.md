> [!NOTE]
Implemenatie moeilijkheidsgraad: gemakkelijk!
> Verdere uitwerking is gestaakt!

# 123LED-Kerstverlichting-IR-31V
<img width="600" height="600" alt="image" src="https://github.com/user-attachments/assets/8c414ad2-5993-4204-9ff7-a60b6827cca9" />

IR-codes zijn afgevangen van [Start-adapter voor koppelbare kerstverlichting | 31V](https://www.123led.nl/123led-Start-adapter-voor-koppelbare-kerstverlichting-31V-i7758-t2096.html)

IR-codes zijn afgevangen via ESPHome en corresponderen met de funties zichtbaar op de afstandsbediening.
ALLE codes zijn in RAW formaat! Deze codes zijn te implementeren via ESPHome middels een IR-transmitter.

Het volgende [ESPhome YAML bestand](https://github.com/AbeltjeNL/123-LED-Kerstverlichting-IR/blob/main/esphome_example.yaml) geeft je de basis, plus een aantal extra sensoren.

> [!NOTE]
```!Pas hierin de ESPHome configuratie aan zodat deze voor jou van toepassing is!```

De transmitter module is vrij goedkoop te vinden op Ali:
[IR transmitter (Dual)](https://nl.aliexpress.com/item/1005008822755413.html?spm=a2g0o.productlist.main.1.424c311bfjJKxK&aem_p4p_detail=2025111616102312006147310864980003321500&algo_pvid=23aa11bf-80ec-4a4f-b53a-6dab64c4f17d&algo_exp_id=23aa11bf-80ec-4a4f-b53a-6dab64c4f17d-0&pdp_ext_f=%7B%22order%22%3A%223%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21EUR%212.90%212.90%21%21%2123.38%2123.38%21%402103956a17633382237446344e506a%2112000046824663054%21sea%21NL%210%21ABX%211%210%21n_tag%3A-29910%3Bd%3A6ba8c67a%3Bm03_new_user%3A-29895&curPageLogUid=WADHPXuYWOkf&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005008822755413%7C_p_origin_prod%3A&search_p4p_id=2025111616102312006147310864980003321500_1)

De reveiver module is vrij goedkoop te vinden op Ali:
[IR recevier](https://nl.aliexpress.com/item/1005008209444057.html?spm=a2g0o.productlist.main.12.2777nfUDnfUD3s&algo_pvid=ee757582-643f-4a08-b5e4-7bd55d845b54&algo_exp_id=ee757582-643f-4a08-b5e4-7bd55d845b54-11&pdp_ext_f=%7B%22order%22%3A%2228%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21EUR%218.88%210.87%21%21%2171.52%217.01%21%402103892f17633384163884488eca67%2112000044241692141%21sea%21NL%210%21ABX%211%210%21n_tag%3A-29910%3Bd%3A6ba8c67a%3Bm03_new_user%3A-29895%3BpisId%3A5000000187474279&curPageLogUid=sqmJXoanmNDO&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005008209444057%7C_p_origin_prod%3A)

> [!WARNING]  
```Dit prodcut (adapter) maakt geluid. Geluid tijdens het afspelen (visueel) van effecten. Deze geluiden zijn hoorbaard vlakbij de adapter!```
```Persoonlijk vind ik dit niet prettig. Luister zelf! Deze geluiden staan los van de impltementatie met ESPHome!```

> [!NOTE]
Gezien dit (vervelende) geluid is de verdere uitwerking gestopt. 
