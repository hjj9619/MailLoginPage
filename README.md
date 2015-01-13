# Mail Login Page

## Parameters

- `domain`: Your custom domain.
- `sp`: Mail service provider.
- `lang`: Your preferred language.
- `logo`: Your logo. If empty, a default logo will be placed.
- `bgimg`: Your custom background image address/uri. If empty, the program will chose one in `$default_bg_path` ramdomly. Pictures in `$default_bg_path` should be 964&times;460 or similar.

## Usage

You can pass the parameters with `GET` method.

Eg. `http://yourdomain/login_page.php?lang=en&sp=163&domain=delbert.me`

Any of the parameter is optional. You may change the default setting by modifying [./inc/config.inc.php](./inc/config.inc.php).

### Language

`lang` option is obeyed ISO 639-1 Language Codes Values and referred from http://www.w3schools.com/tags/ref_language_codes.asp
- [x] `en`: en.
- [x] `zh-Hans`: zh zh_cn zh-hans zh-cn.
- [x] `zh-Hant`: zh-tw zh-hk zh-hant.

### Mail Service Provider

- [ ] 万网： ali wanwang(TO DO)
- [x] 腾讯： tencent tengxun qq (Done)
- [x] 网易： netease 163 126 (Done)
- [ ] Google Apps: google.(Failed to login)
- [ ] Live Domain: microsoft ms(TO DO)
- [ ] Mail.ru: mail.ru biz.mail.ru(TO DO)
- [ ] Zoho Mail: zoho(TO DO)

## Example

You may check the example by visiting http://zhnpng.com/mail .

## License

Under MIT License. See [LICENSE](./LICENSE) for details.
