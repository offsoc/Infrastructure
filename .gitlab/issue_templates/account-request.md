;;;
{
  "title": "Account request",
  "documentation": "https://wiki.gnome.org/Infrastructure/NewAccounts",
  {
    "action": [
      {
        "git_access": {
          "args_key": "module",
          "args_value": "$module_name"
        }
      },
      {
        "maint_access": {
          "args_key": "module",
          "args_value": "$module_name"
        }
      },
      {
        "update_email": {
          "args": "None"
        }
      }
    ]
  }
}

PLEASE ONLY MODIFY THE JSON BELOW, THE ABOVE TEXT IS
IGNORED BY AUTOMATION AND MERELY USED AS DOCUMENTATION.
;;;
{"action": "$action_name", "module": "$module_name"}
