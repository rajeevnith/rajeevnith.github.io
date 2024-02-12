# rajeevnith.github.io

## How I do al-folio?

1. Go to terminal in mac
2. Install docker desktop - https://docs.docker.com/desktop/install/mac-install/ (Don't worry, everyone is using it. So, get used to it!)
3. `git clone https://github.com/alshedivat/al-folio && cd al-folio`
4. `docker compose pull`
5. `docker compose up`
6. Site will be up and running in http://localhost:8080
7. Customise as instructed - https://github.com/alshedivat/al-folio/blob/master/CUSTOMIZE.md
8. If changes are reflecting in http://localhost:8080 then all good otherwise kill (CTRL+c) and run `docker compose up`
9. cd ..
10. `git clone https://github.com/<username>/<username>.github.io.git`
11. `cp -R al-folio/_sites/* <username>.github.io/`
12. `git add .`
13. `git commit -m "update"`
14. `git push origin main`
15. Changes should be published at `<username>.github.io` wihtin 10 mins
16. Chill!
