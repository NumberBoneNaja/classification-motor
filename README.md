# Motor Sound Classification using Deep Learning

โปรเจกต์นี้ใช้เทคนิค Deep Learning ในการจำแนกเสียงของมอเตอร์ออกเป็น 3 ประเภท ได้แก่:
- `engine_broken`: เสียงของมอเตอร์ที่มีปัญหา
- `engine_good`: เสียงของมอเตอร์ที่ทำงานปกติ
- `engine_havyload`: เสียงของมอเตอร์ที่กำลังรับภาระหนัก

## 🔍 วัตถุประสงค์ (Objective)

พัฒนาโมเดล Deep Learning ที่สามารถจำแนกประเภทของเสียงมอเตอร์ได้อย่างแม่นยำ ซึ่งสามารถนำไปใช้ในการวิเคราะห์และตรวจสอบสภาพของเครื่องจักรในภาคอุตสาหกรรม

## 🧠 โมเดลที่ใช้ (Model Architecture)

เราได้ใช้โมเดลผสมระหว่าง:
- **Convolutional Neural Network (CNN)**: สำหรับดึงคุณลักษณะ (features) จาก Spectrogram ของเสียง
- **Long Short-Term Memory (LSTM)**: สำหรับเรียนรู้ลำดับเวลา (temporal patterns) ของเสียง

## 📁 โครงสร้างโปรเจกต์

- แหล่งที่มา: [Electrical Motor Sound Analysis - Kaggle](https://www.kaggle.com/code/pythonafroz/electrical-motor-sound-analysis/input)
- แนวทางการทำ Audio Classification ด้วย Deep Learning และ TensorFlow:**  
  [Audio Classification Using Deep Learning and TensorFlow - A Step-by-step Guide (Medium)](https://medium.com/@oluyaled/audio-classification-using-deep-learning-and-tensorflow-a-step-by-step-guide-5327467ee9ab)
- รูปแบบ: ไฟล์เสียง `.wav` ถูกจัดกลุ่มตามสถานะของมอเตอร์