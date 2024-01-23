# โต้ตอบเทมเพลตเว็บไซต์ JS Resume

![เทมเพลตเว็บไซต์ ReactJS Resume](resume-screenshot.jpg?raw=true 'เทมเพลตเว็บไซต์ ReactJS Resume')

<div align="center">

<img alt="การเปิดตัว GitHub (ล่าสุดตามวันที่รวมถึงเวอร์ชันก่อนเผยแพร่" src="https://img.shields.io/github/v/release/tbakerx/react-resume-template?include_prereleases">

<img alt="ภาษาบนสุดของ GitHub" src="https://img.shields.io/github/languages/top/tbakerx/react-resume-template?style=flat">

<img alt="ส้อม GitHub Repo" src="https://img.shields.io/github/forks/tbakerx/react-resume-template?style=flat&color=success">

<img alt="ดาว GitHub Repo" src="https://img.shields.io/github/stars/tbakerx/react-resume-template?style=flat&color=yellow">

<img alt="เวอร์ชันการพึ่งพา GitHub package.json (prod)" src="https://img.shields.io/github/package-json/dependency-version/tbakerx/react-resume-template/react?style= แบน">

<img alt="ผู้สนับสนุน Github Repo" src="https://img.shields.io/github/sponsors/tbakerx?style=flat&color=blueviolet">

## เทมเพลตที่ใช้ React สำหรับเว็บไซต์เรซูเม่ที่เน้นนักพัฒนาซอฟต์แวร์

</div>

### ดู [การสาธิตสดที่นี่](https://reactresume.com)

#### หากเทมเพลตนี้ช่วยคุณได้และต้องการสนับสนุนงานของฉัน โปรด [♥ Sponsor](https://github.com/sponsors/tbakerx) โปรเจ็กต์ได้ตามใจชอบ

### 🎉 เวอร์ชัน 2 มาแล้ว! คุณสมบัติใหม่:
1. สร้างใหม่ทั้งหมดด้วย React และรองรับ typescript เต็มรูปแบบ
2. สร้างขึ้นบนเฟรมเวิร์ก [Next.js](https://nextjs.org/) เพื่อการเรนเดอร์ฝั่งเซิร์ฟเวอร์/การสร้างสแตติกที่ง่ายดาย การเพิ่มประสิทธิภาพรูปภาพ เส้นทาง API และการปรับใช้
3. ตกแต่งสไตล์ทั้งหมดด้วย [TailwindCss](https://tailwindcss.com/)
4. จัดระเบียบไฟล์ข้อมูลประชากรใหม่สำหรับปรับแต่งไซต์
5. การปรับปรุง/ปรับปรุงส่วนต่างๆ ของไซต์ทั้งหมดอย่างมีนัยสำคัญ
 
**กำลังมองหาเวอร์ชันเก่าอยู่ใช่ไหม? ดูได้[ที่นี่](https://github.com/tbakerx/react-resume-template/releases/tag/v1.0.0)**

## คำอธิบาย

นี่คือเทมเพลตเว็บไซต์เรซูเม่ส่วนตัวที่ใช้ React สร้างด้วย typescript บนเฟรมเวิร์ก Next.js ตกแต่งสไตล์ด้วย Tailwind css และเติมข้อมูลจากไฟล์เดียว คุณสามารถสร้าง ปรับแต่ง และโฮสต์เว็บไซต์ส่วนตัวของคุณเองได้อย่างง่ายดายภายในไม่กี่นาที ยิ่งไปกว่านั้น ไซต์ได้รับการปรับให้เหมาะสมสำหรับมือถืออย่างสมบูรณ์และเรนเดอร์ฝั่งเซิร์ฟเวอร์เพื่อให้แน่ใจว่าจะโหลดได้รวดเร็วและ UI ที่สะอาดบนอุปกรณ์ทุกชนิด อ่านต่อเพื่อเรียนรู้วิธีสร้างมันขึ้นมาเอง

## ทำให้เป็นของคุณเอง!

### 1. ตรวจสอบให้แน่ใจว่าคุณมีสิ่งที่คุณต้องการ

หากต้องการสร้างเว็บไซต์นี้ คุณจะต้องดาวน์โหลดและติดตั้ง Node และ Yarn เวอร์ชันเสถียรล่าสุดบนเครื่องของคุณ หากยังไม่มี คุณสามารถดาวน์โหลด Node ได้ [ที่นี่](https://nodejs.org/en/download/) และ Yarn [ที่นี่](https://yarnpkg.com/getting-started/ ติดตั้ง)

### 2. แยกและดาวน์โหลด repo นี้ (และติดดาวถ้าคุณต้องการ!)

จากนั้นหาปุ่ม `Fork` ที่มุมขวาบนของหน้านี้ ซึ่งจะทำให้คุณสามารถสร้างสำเนาของคุณเองได้ สำหรับข้อมูลเพิ่มเติมเกี่ยวกับการ fork repo โปรดดู [ที่นี่](https://docs.github.com/en/get-started/quickstart/fork-a-repo#forking-a- repository) หลังจากนี้ ให้ดาวน์โหลดไปยังเครื่องพัฒนาของคุณโดยใช้ปุ่ม `Code` สีเขียวที่ด้านบนของหน้า repo

### 3. ติดตั้งการอ้างอิงและเรียกใช้

เมื่อคุณมีสำเนาของ repo นี้แยกและดาวน์โหลดแล้ว ให้เปิดโฟลเดอร์ในเทอร์มินัลที่คุณชื่นชอบแล้วเรียกใช้ `yarn install` เพื่อติดตั้งการอ้างอิง ต่อไปนี้ ให้รัน `yarn dev` เพื่อรันโปรเจ็กต์ ในเทอร์มินัลของคุณ คุณควรได้รับ URL ของอินสแตนซ์ที่ทำงานอยู่ (โดยปกติจะเป็น http://localhost:3000 เว้นแต่ว่าคุณมีสิ่งอื่นที่ทำงานอยู่)

### 4. ปรับแต่งข้อมูลเพื่อให้เป็นของคุณเอง

ข้อมูลทั้งหมดสำหรับไซต์ขับเคลื่อนผ่านไฟล์ที่ `/src/data/data.tsx` ที่นี่คุณจะพบเนื้อหาที่มีอยู่ที่นี่ และการอัปเดตค่าต่างๆ ที่นี่จะแสดงบนเว็บไซต์ หากคุณมีไซต์ทำงานตามที่อธิบายไว้ข้างต้น คุณควรเห็นการเปลี่ยนแปลงเหล่านี้แสดงในการบันทึก ประเภทข้อมูลสำหรับรายการทั้งหมดเหล่านี้อยู่ในโฟลเดอร์เดียวกันในไฟล์ `dataDef.ts` รูปภาพตัวอย่างสามารถดูได้ที่ `src/images/` และนำเข้าในไฟล์ข้อมูล หากต้องการเปลี่ยนแปลง เพียงอัปเดตรูปภาพเหล่านี้โดยใช้ชื่อและตำแหน่งเดียวกัน หรือเพิ่มรูปภาพใหม่และอัปเดตการนำเข้า

### 5. ขอแบบฟอร์มการติดต่อ
เนื่องจากมีตัวเลือกมากมายสำหรับผู้ให้บริการแบบฟอร์มการติดต่อ ฉันจึงเชื่อมต่อแบบฟอร์มการติดต่อเฉพาะในส่วนที่เกี่ยวข้องกับอินพุตและสถานะเท่านั้น การส่งแบบฟอร์มและการส่งอีเมลจริงนั้นเปิดให้นำไปใช้ได้เอง คำแนะนำส่วนตัวของฉันสำหรับผู้ให้บริการอีเมลคือ [Sendgrid.](https://sendgrid.com/)

### 6. ทำการเปลี่ยนแปลงอื่นๆ ตามที่คุณต้องการ

แน่นอนว่าโค้ดทั้งหมดอยู่ที่นั่นและไม่มีอะไรถูกซ่อนไว้จากคุณ ดังนั้นหากคุณต้องการเปลี่ยนแปลงสไตล์/ข้อมูลอื่นๆ อย่าลังเลที่จะ!

### 7. ปรับใช้กับ Vercel และเพลิดเพลินกับเว็บไซต์เรซูเม่ใหม่ของคุณ

การปรับใช้ไซต์ใหม่ของคุณกับ Vercel นั้นง่ายดาย และทำได้โดยทำตามคำแนะนำของพวกเขา [ที่นี่](https://vercel.com/guides/deploying-nextjs-with-vercel) เมื่อคุณดำเนินการทั้งหมดเสร็จแล้วและสร้างบิวด์สำเร็จ คุณควรได้รับ URL สำหรับเว็บไซต์ที่ใช้งานอยู่ของคุณ ไปที่นั่นแล้วคุณจะเห็นเว็บไซต์ประวัติส่วนตัวใหม่ของคุณ! ยินดีด้วย!

## โครงการที่สร้างและดูแลโดย

### Tim Baker

<a href="https://twitter.com/timbakerx"><img src="https://github.com/aritraroy/social-icons/blob/master/twitter-icon.png?raw=true" width="60"></a> <a href="https://instagram.com/tbakerx"><img src="https://github.com/aritraroy/social-icons/blob/master/instagram-icon.png?raw=true" ความกว้าง ="60"></a>

[![ผู้ติดตาม GitHub](https://img.shields.io/github/followers/tbakerx.svg?style=social&label=Follow)](https://github.com/tbakerx/)

## สตาร์เกเซอร์

[![บัญชีรายชื่อ repo Stargazers สำหรับ @tbakerx/react-resume-template](https://reporoster.com/stars/dark/tbakerx/react-resume-template)](https://github.com/tbakerx/react -เรซูเม่เทมเพลต/นักดูดาว)

## ฟอร์เกอร์

[![บัญชีรายชื่อ repo ของ Forkers สำหรับ @tbakerx/react-resume-template](https://reporoster.com/forks/dark/tbakerx/react-resume-template)](https://github.com/tbakerx/react -เรซูเม่-แม่แบบ/เครือข่าย/สมาชิก)