in settings.py / installed apps
'users.apps.UsersConfig',
'crispy_forms',
'crispy_bootsrap5',


AUTH_USER_MODEL = 'users.MyUser'

LOGIN_REDIRECT_URL = 'home'
LOGOUT_REDIRECT_URL = 'home'

CRISPY_ALLOWED_TEMPLATE_PACKS='bootstrap5'
CRISPY_TEMPLATE_PACK = 'bootstrap5'
