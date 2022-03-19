Intialization:
from .environs import Env
env=Env()
env.read_env() # read .env file, if it exists
SECRET_KEY=env.str("SECRET_KEY")
Requires:

1. marshmallow : https://pypi.org/project/marshmallow/
2. python-dotenv : https://pypi.org/project/python-dotenv/
