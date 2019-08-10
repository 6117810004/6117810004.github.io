# Requirement ID : V8.3.7

Requirement Detail : Verify that sensitive or private information that is required to be encrypted, is encrypted using approved algorithms that provide both confidentiality and integrity.

OTG #1 : Testing for Weak SSL/TLS Ciphers, Insufficient Transport Layer Protection (OTG-CRYPST-001)
* ทดสอบ Weak SSL/TLS จะต้องเป็นเวอร์ชันที่ไม่มีช่องโหว่ เวอร์ชันล่าสุดจะมีการป้องกันการรั่วไหลของข้อมูล และต้องป้องกันการใช้ Transport Layer ไม่เพียงพอ

OTG #2 : Testing for Sensitive information sent via unencrypted channels (OTG-CRYPST-003)
* ทดสอบในส่ง Sensitive Information ผ่านช่องทางที่ไม่มีการเข้ารหัสลับ
