# Top NoScope ( Dürbünsüz Vuruş Sıralaması )

Eklenti dürbünsüz leş alan oyuncuya 1 puan verir ve onu tabloya aktarır.

## Eklenti Kurulum:

1. WebFTP/FTP üzerinden addons/sourcemod/configs yoluna gidiyoruz, **databases.cfg** dosyasına giriyoruz ve aşağıda size verdiğim kısmı oraya kopyalayıp yapıştırıyorsunuz.
```json	
	"topns"
	{
		"driver"			"sqlite"
		"database"			"topns"
	}
```
2. WebFTP/FTP üzerinden addons/sourcemod/plugins yoluna gidiyoruz ve size verdiğim addons/sourcemod/plugins/**topns.smx** eklentisini oraya atıyoruz.

3. Sunucunuzu restartlayın ve eklentiniz çalışacaktır.

## Eklenti Komutları:

#### Sıralamayı açma komutları:
1. sm_topns
2. sm_topnoscope 

#### Sıralamayı panele loglama komutları:
1. sm_topnslog
2. sm_topnoscopelog

#### Sıralamayı sıfırlama komutları:
1. sm_xtopnslog
2. sm_xtopnoscopelog
