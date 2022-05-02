# directadmin_ua_ru_lang
Український та російський переклад для DirectAdmin
```
cd /usr/local/directadmin/data/skins/evolution/lang/  
wget https://github.com/kovaliovyuriy/directadmin_ua_ru_lang/archive/refs/heads/main.zip  
unzip main.zip  
mv directadmin_ua_ru_lang-main/* ./
rm -rf directadmin_ua_ru_lang-main main.zip  
chown -R diradmin:diradmin /usr/local/directadmin/data/skins/evolution/lang/  
service directadmin restart  
```
