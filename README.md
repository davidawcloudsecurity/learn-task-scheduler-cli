# How to run task scheduler in Windows using cli
```ruby
schtasks /create /tn "ShutdownAt6PM" /tr "shutdown /s /f /t 0" /sc daily /st 18:00 /ru SYSTEM
```
remove
```ruby
schtasks /delete /tn "ShutdownAt6PM" /f
```
