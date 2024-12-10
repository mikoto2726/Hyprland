slackやDiscordのアプリケーションで日本語が入力できない問題の解決策   

sudo nvim /usr/share/applications/slack.desktop 
xec行を以下のように変更します：   
Exec=slack --enable-features=UseOzonePlatform --ozone-platform=x11

sudo nvim /usr/share/applications/discord.desktop 
xec行を以下のように変更します：  
Exec=/usr/bin/discord --enable-features=UseOzonePlatform --ozone-platform=x11   
systemctl --user restart xdg-desktop-portal

