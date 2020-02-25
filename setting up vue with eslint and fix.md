npm install -g @vue/cli

vue create <project name>

npm install prettier eslint -g
npm install eslint-plugin-prettier eslint-config-prettier --save-dev

"eslintConfig": {
    "root": true,
    "extends": [
      "plugin:vue/essential",
      "plugin:prettier/recommended",
      "eslint:recommended"
    ]
  },
