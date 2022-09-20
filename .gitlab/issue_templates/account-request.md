;;;
{
  "title": "Account request",
  "documentation": "https://wiki.gnome.org/Infrastructure/NewAccounts",
  {
    "action": [
      {
        "new_account": {
          "args_key": "module",
          "args_value": "${module_name}"
        }
      },
      {
        "git_access": {
          "args_key": "module",
          "args_value": "${module_name}"
        }
      },
      {
        "maint_access": {
          "args_key": "module",
          "args_value": "${module_name}"
        }
      },
      {
        "email_update": {
          "args": "None"
        }
      }
    ]
  }
;;;
{"action": "${action_name}", "module": "${module_name}"}
