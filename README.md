# random_user_agent
provided the random user-agent for spider-developer to prevent forbiding from web-server

# usage:
- download this python file;
- move it to your python interpreter installed path which directory named `site-packages`;
- use this code in your project:
  - `from random_user_agent import get_ua`
  - `headers["User-Agent"] = get_ua`
