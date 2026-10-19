# Updating to version 2 (cross icon, several teachers, iPhone web app)

1. Firebase -> Firestore -> Rules: paste firestore.rules -> Publish.
2. Firebase -> Firestore -> Data -> teachers -> your document -> Add field: admin (boolean) = true.
3. Upload all files from this folder to your GitHub repo (replace old ones).
4. Edit .github/workflows/build-apk.yml on GitHub and paste the new content from this folder.
5. Repo -> Settings -> Pages -> Source: GitHub Actions (repo must be public on a free account).
6. Firebase -> Authentication -> Settings -> Authorized domains -> add <your-github-username>.github.io
7. Actions: wait for both jobs. APK: download ruhi-apk. Web: open the link shown in the "web" job.
8. iPhone: open the link in Safari -> Share -> Add to Home Screen.
