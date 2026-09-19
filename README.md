# CatFeth's Mihomo-Templates

---
## Template *Quantum Direct*

⚫ All trafic -> Direct,
⚫ Routing for Russian's Sites and IP's, ASN's and Apps,
⚫ Routing for many popular Sites, IP's, ASN's and Apps

---
## Template *Quantum Proxy* (Alternative version Q-Direct, less rules)

⚫ All trafic -> Proxy,
⚫ Routing for Russian's Sites and IP's, ASN's and Apps

---
## Template *Quantum Direct & Quantum Proxy for 3X-UI*

These configurations include the default q-direct and q-proxy settings + special values to ensure the Clash configuration works properly in the <b>[3X-UI-Pro](https://github.com/mozaroc/3x-ui-pro)<b>.

### Guide:

#### RU:
Для замены шаблона mihomo(clash) в инсталляции 3X-UI-Pro, необходимо:
1. Скачать файл q-direct-3x.yaml или q-proxy-3x.yaml, найти строку №143 и заменить 
https://${DOMAIN}/${SUB_PATH}/${SUB_ID} на url вашей реальной подписки из 3X-UI-Pro
2. На сервере где установлен 3X-UI-Pro, заменить содержимое файла /var/www/subpage/clash.yaml.tpl на новый шаблон из п.1

#### EN:
To replace the mihomo(clash) template in a 3X-UI-Pro installation, you must:
1. Download the q-direct-3x.yaml or q-proxy-3x.yaml file, locate line 143 and replace 
https://${DOMAIN}/${SUB_PATH}/${SUB_ID} with the URL of your actual 3X-UI-Pro subscription
2. On the server where 3X-UI-Pro is installed, replace the contents of the file /var/www/subpage/clash.yaml.tpl with the new template from step 1

---
## ASN

⚫ Rule-set Russian ASN
⚫ Rule-set CDN ASN

---
## Geo

⚫ Rule-set for domains & ip/cidr

---
## Thanks 
<b>[Legiz](https://github.com/legiz-ru)<b> and <b>[Davoyan](https://github.com/Davoyan)<b>,
<b>[Skaat](https://github.com/skaat-mf)<b> and <b>[Leh](https://github.com/Inrd-sknrd)<b>
