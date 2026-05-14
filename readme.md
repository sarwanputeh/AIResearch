postman request POST 'https://eight-bears-fix.loca.lt/v1/chat/completions
' \
  --header 'Content-Type: application/json' \
  --body '{
  "model": "Qwen/Qwen2.5-1.5B-Instruct",
  "messages": [
    {
      "role": "user",
      "content": "ทำนายอากาศวันนี้ให้หน่อย"
    }
  ]
}


'

---------------------

# อัปเดตรายการ package ก่อน
sudo apt update
# ติดตั้ง Python 3, pip และตัวช่วย map คำสั่ง (ถ้าถามรหัสผ่าน ให้ใส่รหัสตอนเข้า Linux)
sudo apt install python3 python3-pip python-is-python3 -y
