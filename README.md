# filehost 📁
An open source file host that you can easily selfhost. Made by the creators of file.coffee.

![https://raw.githubusercontent.com/filecoffee/filehost/main/assets/git/homepage.png](https://raw.githubusercontent.com/filecoffee/filehost/main/assets/git/homepage.png)

## Simply start your own file host 🚀
filehost is a one-click (or one-command) setup file host that you can deploy wherever you want. Full control over your own data. No limits.

### Use Railway (one-click) (W.i.p) 🚂
Hit the Railway button and have your filehost up and running in a few minutes. The button also supports the project since we get a small referral bonus.

[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/template/pv_x6t?referralCode=QsZ-bg)


### DIY - Docker! 🐳
Simply run `docker-compose up --build -d` on your server after you've configured the `.env` and it's all up and running.

```
Note: We're still actively working on the product and is currently in early alpha stages. We currently recommend also making a backup or chosing S3 as a host with the project.
```

We also recommend forking the project and deploying your forked version to avoid issues when we push updates. You can then easily merge the changes in your forked version.

## Roadmap 🛣️
- [x] File uploads
- [x] Retrieving files
- [x] Unit tests
- [x] File size limits
- [x] ShareX integration
- [x] Allow public uploads
- [x] Basic API keys
- [ ] Whitelisting file types
- [ ] User authentication <-- Currently in development
- [ ] File deletion
- [ ] File expiration
- [ ] File management
- [ ] File statistics
- [ ] File search
- [ ] File tagging using AI
- [ ] File previews
- [x] Rate limiting
- [x] Slowdown on too many requests
- [ ] Advertising support
- [ ] NSFW detection and filtering

### S3 Compatible Storage
For the s3 compatbile storage engine, we recommend using Contabo Object Storage. It's a cheap (2,50/mth for 250GB with unlimited bandwidth at 80mbps) and really easy to set up. Just make an account, get the object storage, make a bucket and fill in the details in the `.env` and it _just works_.

## Note
It's currently a big work in progress. But stay patient, something you can deploy will be ready a.s.a.p.
