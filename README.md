## Example Playbook

    - hosts: all
      tasks:
        - import_role:
            name: mmcnl.ssmtp
          vars:
            ssmtp_notification_email: admin@example.com

            ssmtp_server: smtp.gmail.com
            ssmtp_port: 587
            ssmtp_user: my_user
            ssmtp_password: password123

## License

MIT

