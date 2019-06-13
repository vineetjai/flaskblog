# flaskblog


1. Add config.json in which there has to `SECRET_KEY` to your app, `SQLALCHEMY_DATABASE_URI`, `MAIL_USERNAME` and `MAIL_PASSWORD`
it has to be like:-

```
{	
	"SECRET_KEY":"your scerect key generated using secrets python package",
	"SQLALCHEMY_DATABASE_URI":"sqlite:///site.db",
	"MAIL_USERNAME":"mail@domain.com", 
	"MAIL_PASSWORD":"mail_password"
}
```

2. Change path in config.py inside flaskblog directory to your path in open command
