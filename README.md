# SonarQube with Let's Encrypt in a Docker Compose

Install Docker Engine and Docker Compose by following my [guide](https://www.heyvaldemar.com/install-docker-engine-and-docker-compose-on-ubuntu-server/).

Run `sonarqube-restore-application-data.sh` to restore application data if needed.

Run `sonarqube-restore-database.sh` to restore database if needed.

Deploy SonarQube server with a Docker Compose using the command:

`docker compose -f sonarqube-traefik-letsencrypt-docker-compose.yml -p sonarqube up -d`

Detailed installation guide can be found on my [website](https://www.heyvaldemar.com/install-sonarqube-with-docker-compose/).

# Infrastructure Model
![Infrastructure model](.infragenie/infrastructure_model.png)

# Author
hey, I’m Vladimir Mikhalev, but my friends call me Valdemar.

🌐 My [website](https://www.heyvaldemar.com/) with detailed IT guides\
🎬 Follow me on [YouTube](https://www.youtube.com/channel/UCf85kQ0u1sYTTTyKVpxrlyQ?sub_confirmation=1)\
🐦 Follow me on [Twitter](https://twitter.com/heyValdemar)\
🎨 Follow me on [Instagram](https://www.instagram.com/heyvaldemar/)\
🎸 Follow me on [Facebook](https://www.facebook.com/heyValdemarFB/)\
🎥 Follow me on [TikTok](https://www.tiktok.com/@heyvaldemar)\
💻 Follow me on [LinkedIn](https://www.linkedin.com/in/heyvaldemar/)\
🐈 Follow me on [GitHub](https://github.com/heyvaldemar)

# Communication
👾 Chat with IT pros on [Discord](https://discord.gg/AJQGCCBcqf)\
📧 Reach me at ask@sre.gg

# Give Thanks
💎 Support on [GitHub](https://github.com/sponsors/heyValdemar)\
🏆 Support on [Patreon](https://www.patreon.com/heyValdemar)\
🥤 Support on [BuyMeaCoffee](https://www.buymeacoffee.com/heyValdemar)\
🍪 Support on [Ko-fi](https://ko-fi.com/heyValdemar)\
💖 Support on [PayPal](https://www.paypal.com/paypalme/heyValdemarCOM)
