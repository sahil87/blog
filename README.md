# Blog

### To work with hexo

#### New Project

> https://hexo.io/docs/setup.html

```
$ hexo init <folder> #For new projects
$ cd <folder>
$ npm install
```

#### Existing Project

* Clone repo
* `yarn global add hexo-cli`
* Checkout already existing submodules in this project:
  ```
  git submodule update --init --recursive
  ```
* Add optional plugins for theme-next (out of source-control)
  ```
  git clone https://github.com/theme-next/theme-next-fancybox3 themes/next/source/lib/fancybox
  ```
* Use Hexo Admin: `hexo server -d`, Open http://localhost:4000/admin/
* One Shot Commit/Deploy `./hexo-deploy.sh`

### Shortcuts

* Create a new post `hexo new "My New Post"`
> More info: [Writing](https://hexo.io/docs/writing.html)
* Generate static files `hexo generate`
> More info: [Generating](https://hexo.io/docs/generating.html)

### To add a submodule (hexo theme)
`git submodule add https://github.com/theme-next/hexo-theme-next themes/next` 

**Main documentation:** https://hexo.io/docs/

**Configuration:** https://hexo.io/docs/configuration.html
