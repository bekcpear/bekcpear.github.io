## Postfix结构图解
```
  MUA ---------------------------------- MTA - MDA ---------- MRA - MUA
        main.cf:smtpd_client_restrictions-|                    |-smtpd_sender_restricitons
     main.cf:smtpd_recipient_restrictions-|
        main.cf:smtpd_replay_restrictions-|
```
H
