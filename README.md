# CSS-collections

# Elements (Selectors)

- `* { }`  
  เลือกทุก element - เลือกทุกองค์ประกอบในหน้าเว็บ
- `div { }`  
  เลือกทุก div elements - เลือกทุก div บนหน้าเว็บ
- `div, p { }`  
  เลือกทุก div และ p elements - เลือกทั้ง div และ p พร้อมกัน
- `div p { }`  
  เลือก p elements ที่อยู่ใน div - เลือก p ที่อยู่ภายใน div ไม่ว่าจะลึกเท่าใด
- `div > p { }`  
  เลือก p elements ที่เป็นลูกโดยตรงของ div
- `div + p { }`  
  เลือก p elements ที่อยู่ติดกับ div ทันที
- `div ~ p { }`  
  เลือก p elements ทั้งหมดที่อยู่หลัง div และมีพ่อแม่เดียวกัน
- `.class { }`  
  เลือก elements ที่มี `class="class"`
- `#id { }`  
  เลือก element ที่มี `id="id"`
- `[attr] { }`  
  เลือก elements ที่มีแอตทริบิวต์ `attr`
- `[attr=val] { }`  
  เลือก elements ที่มี `attr="val"`

# สี (Colors)

- `color: #ff0000;` — สีแบบ Hex code
- `color: rgb(255, 0, 0);` — สีแบบ RGB
- `color: rgba(255, 0, 0, 0.5);` — สีแบบ RGBA (โปร่งใสได้)
- `color: hsl(0, 100%, 50%);` — สีแบบ HSL
- `color: hsla(0, 100%, 50%, 0.5);` — สีแบบ HSLA (โปร่งใสได้)
- `color: red;` — ใช้ชื่อสีมาตรฐาน

# ข้อความ (Text)

- `font-family: Arial, sans-serif;` — กำหนดชนิดฟอนต์
- `font-size: 16px;` — กำหนดขนาดตัวอักษร
- `font-weight: bold;` — ความหนาของตัวอักษร
- `font-style: italic;` — รูปแบบตัวอักษร
- `text-align: center;` — จัดตำแหน่งข้อความ
- `text-decoration: underline;` — การตกแต่งข้อความ
- `text-transform: uppercase;` — การแปลงข้อความ
- `line-height: 1.5;` — ความสูงบรรทัด
- `letter-spacing: 2px;` — ระยะห่างตัวอักษร
- `word-spacing: 5px;` — ระยะห่างระหว่างคำ
- `text-shadow: 2px 2px 5px #000000;` — เงาข้อความ
- `white-space: nowrap;` — จัดการพื้นที่ว่างในข้อความ

# พื้นหลัง (Background)

- `background-color: #f0f0f0;` — สีพื้นหลัง
- `background-image: url('image.jpg');` — รูปภาพพื้นหลัง
- `background-repeat: no-repeat;` — การทำซ้ำของพื้นหลัง
- `background-position: center center;` — ตำแหน่งรูปพื้นหลัง
- `background-size: cover;` — ขนาดรูปพื้นหลัง
- `background-attachment: fixed;` — พื้นหลังคงที่
- `background: #f0f0f0 url('image.jpg') no-repeat center/cover;` — เขียนแบบรวม

# การจัดวาง (Layout)

- `display: block;` — ลักษณะการแสดงผล
- `position: relative;` — วิธีการจัดตำแหน่ง
- `top: 10px;` — ระยะห่างจากขอบบน
- `right: 10px;` — ระยะห่างจากขอบขวา
- `bottom: 10px;` — ระยะห่างจากขอบล่าง
- `left: 10px;` — ระยะห่างจากขอบซ้าย
- `float: left;` — ลอยซ้าย
- `clear: both;` — ควบคุมการลอย
- `z-index: 1;` — ลำดับชั้นการซ้อน

# กล่อง (Box Model)

- `width: 100px;` — ความกว้าง
- `height: 100px;` — ความสูง
- `max-width: 100%;` — ความกว้างสูงสุด
- `min-width: 50px;` — ความกว้างต่ำสุด
- `max-height: 100%;` — ความสูงสูงสุด
- `min-height: 50px;` — ความสูงต่ำสุด
- `margin: 10px;` — ระยะขอบนอก
- `padding: 10px;` — ระยะขอบใน
- `border: 1px solid black;` — เส้นขอบ
- `border-radius: 5px;` — ความโค้งของขอบ
- `box-sizing: border-box;` — วิธีคำนวณขนาด
- `overflow: auto;` — จัดการเนื้อหาที่ล้น

# Flexbox

- `display: flex;` — เปิดใช้งาน Flexbox
- `flex-direction: row;` — ทิศทางเรียง
- `flex-wrap: wrap;` — ขึ้นบรรทัดใหม่
- `flex-flow: row wrap;` — รวมทิศทางและการขึ้นบรรทัด
- `justify-content: center;` — จัดตำแหน่งตามแนวหลัก
- `align-items: center;` — จัดตำแหน่งตามแนวขวาง
- `align-content: center;` — จัดตำแหน่งแถวตามแนวขวาง
- `order: 1;` — ลำดับการแสดง
- `flex-grow: 1;` — การขยาย
- `flex-shrink: 1;` — การหดตัว
- `flex-basis: auto;` — ขนาดเริ่มต้น
- `flex: 1;` — รวม grow, shrink, basis
- `align-self: center;` — จัดตำแหน่งเฉพาะ item

# Grid

- `display: grid;` — เปิดใช้งาน Grid
- `grid-template-columns: 100px 100px 100px;` — ความกว้างคอลัมน์
- `grid-template-rows: 100px 100px;` — ความสูงแถว
- `grid-template-areas: "header header" "sidebar main" "footer footer";` — กำหนดพื้นที่
- `grid-column-gap: 10px;` — ช่องว่างระหว่างคอลัมน์
- `grid-row-gap: 10px;` — ช่องว่างระหว่างแถว
- `grid-gap: 10px 10px;` — รวม row-gap และ column-gap
- `grid-column: 1 / 3;` — ตำแหน่งคอลัมน์
- `grid-row: 1 / 3;` — ตำแหน่งแถว
- `grid-area: main;` — พื้นที่ด้วยชื่อ

# การเปลี่ยนแปลง (Transforms)

- `transform: translate(50px, 50px);` — เคลื่อนย้าย
- `transform: scale(1.5);` — ขยายขนาด
- `transform: rotate(45deg);` — หมุน
- `transform: skew(10deg, 10deg);` — เอียง
- `transform: matrix(1, 0.5, 0.5, 1, 50, 50);` — เมทริกซ์ซับซ้อน
- `transform-origin: center center;` — จุดศูนย์กลางการเปลี่ยนแปลง

# Animation และ Transition

- `transition: property duration timing-function delay;` — รูปแบบเต็มของ transition
- `transition: all 0.3s ease 0s;` — ตัวอย่าง transition ทั้งหมด
- การกำหนด Animation:
  ```css
  @keyframes slidein {
    from { transform: translateX(0); }
    to { transform: translateX(100px); }
  }
