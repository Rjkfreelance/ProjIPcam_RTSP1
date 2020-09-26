# ProjIPcam_RTSP1
ให้บอม Clone project  ติดตั้ง เข้าไปใน C:\ProjIPcam_RTSP1  ใช้ คำสั่ง npm install   จะ Load จาก package.json 
ในเคื่อง ให้ติดตั้ง http server  ใช้ ตำสั่ง  npm install http-server -g 
และ ให้ ติดตั้ง Program ffmpeg     c:\ffmpeg\bin   set ใน path 
เปิด cmd หนเาต่าง DOS  2 หน้าต่าง 
เรียก  run http-server  ใน Folder c:\ProjIPcam_RTSP1  เรียก  http-server (เป็นการ Start Web server)
และอีก หน้าต่าง  run   node rtspcamtest.js (เป็น การ Start RTSP Server)

  ใน ฺBrowser เปิด  Code web    http://localhost:8080 ก็จะดูกล้องได้  (เรียก web socket ตอนนี้ ทดสอบกล้อง สาธารณะ กำหนดไว้ 2 Ports 9000,9999
  
