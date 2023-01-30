;;;
{
  "title": "Account request",
  "documentation": "https://wiki.gnome.org/Infrastructure/NewAccounts",
  {
    "action": [
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
        "update_email": {
          "args": "None"
        }
      }
    ]
  }
;;;
{"action": "${action_name}", "module": "${module_name}"}
