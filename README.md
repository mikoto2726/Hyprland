sudo nvim /usr/share/applications/slack.desktop 
xec行を以下のように変更します：   
Exec=env QT_IM_MODULE=fcitx GTK_IM_MODULE=fcitx XMODIFIERS=@im=fcitx slack

