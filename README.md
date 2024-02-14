# rajeevnith.github.io

## How I do al-folio?

1. Install docker desktop - https://docs.docker.com/desktop/install/mac-install/ (Don't worry, everyone is using it. So, get used to it!)
2. Go to the terminal in mac
3. `git clone https://github.com/alshedivat/al-folio && cd al-folio`
4. `docker compose pull`
5. `docker compose up`
6. Site will be up and running at `http://0.0.0.0:8080/al-folio` (By default doesn't work in Safari, try Chrome)
7. Customise as instructed - `https://github.com/alshedivat/al-folio/blob/master/CUSTOMIZE.md`
8. If changes are reflected in `http://0.0.0.0:8080/al-folio` then all is good otherwise kill (CTRL+c) and run `docker compose up`
9. cd ..
10. `git clone https://<username>:<personal_token>@github.com/<username>/<github_username>.github.io.git`
11. `cp -R al-folio/_site/* <username>.github.io/`
12. `cd <username>.github.io/`
13. `git add .`
14. `git commit -m "update"`
15. `git push origin main`
16. Changes should be published at `<username>.github.io` within 10 mins
17. Chill!
