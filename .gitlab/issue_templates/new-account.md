### Account details

Please provide the following information:

1. Your full name
2. Permanent email address
3. Requested account name. Please note nicknames are NOT allowed (https://wiki.gnome.org/AccountsTeam/AccountNamePolicy)
4. Explanation why you think you should get an account

Once your account has been created, you should be able to reset your GNOME Account password via:

https://password.gnome.org

Once done, please login with your username and the password you just set at the following website:

https://account.gnome.org

You will then be able to manage your account including adding SSH keys which will then be automatically
syncronized against GitLab. Please also remember your GNOME Account allows you to login to all the hosted services
including Discourse, Events website, Pastebin, Nextcloud, Gitlab etc.

Note: We require RSA (4096 preferred). Use `ssh-keygen -t rsa -b 4096`. Please make sure your key matches all 
the requirements listed at https://wiki.gnome.org/AccountsTeam/SSHKeyGuidelines before adding it. 

/label ~new-account
/cc @averi
/confidential
