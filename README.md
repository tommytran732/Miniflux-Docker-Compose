# Miniflux-Docker-Compose
Miniflux Docker-Compose

1. Update `docker-compose.yml`
2. Update the hostname in `swag/nginx/proxy-confs/miniflux.subdomain.conf` approprieately.
3. Run `docker-compose up` and make sure nothing errors out. You can use `docker-compose up -d` to start it in the background if you want.
4. (Optional) Apply `style.css` in the `Custom CSS` section in settings. This theme is from [reeseovine/miniflux-midnight](https://github.com/reeseovine/miniflux-midnight), I just removed the google remote google CSS lines as they are not necessary and cause issues with CSP. There is no license file in the repository or its upstream unfortunately.