# ccr-hugo
hugo raw files for the website

https://ccr-china.github.io/

## logs
- 20241216 github-action file 404 error
   -  change hugo-version: "0.139.2" # 'latest'
   - refer to this issue https://github.com/peaceiris/actions-hugo/issues/662
- 20241111 debug errors  public & private key

```
ssh-keygen -t rsa -b 4096 -C "$(git config user.email)" -f ~/.ssh/gh-pages-2 -N ""
```
