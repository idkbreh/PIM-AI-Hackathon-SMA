# PIM AI Contest 2024

**Project Detail**
- Project name : SMA ( Supermarket Assistant ) 
- Type : Ai model ( CiRa Core )
- Loss Function : 0.07 ( 2024-11-06 )

## Concept

  ต้องการเริ่มโปรเจคที่สามารถต่อยอดไปได้หลายทาง ทางทีมพัฒนาเราจึงได้พัฒนาโปรเจคนี้ในฐานะ AI MODEL ซึ่งทุกคนที่อยากนำไปใช้ในเชิงพาณิชย์หรือเพื่อการศึกษานั้นสามารถนำไปใช้ได้ง่ายๆ เพียงดาวน์โหลดแล้วนำไปเข้าโปรแกรม Low-code Ai Platform อย่าง CiRA Core หรือสามารถ import เข้าใน Python ได้

## Install

```bash
git clone https://github.com/idkbreh/PIM-AI-Hackathon-SMA.git
# unzip then select a SMA folder and put it in Deeptrain CiRA Core platform
# unzip and import into your python project 
```

## About SMA

หลักการทำงานของ SMA MODEL คือการนำรูปภาพของสินค้ามาฝึกด้วยโรแกรมสำเร็จรูปอย่าง CiRA Core โดยเริ่มจากการ Label ตัวสินค้าทีละชนิด แล้วนำไปฝึกบน [Google Colab](https://colab.research.google.com/github/CiRA-AMI/cira-colab-trainer/blob/main/CiRA_DeepTrain_Colab.ipynb) เมื่อทำการ Train Model สำเร็จเราจึงนำ Model ที่ได้ไปเทสเบื้องต้น โดยมีข้อมูลทางสถิติดังนี้
- ค่า loss function : 0.07
- ความแม่นยำขณะทดสอบด้วยรูปนิ่ง : 99%
- ค่า Threshold ที่ตั้งค่าไว้ : 50%
- จำนวนรูปใน Dataset ของ Model นี้ : 226 รูป สินค้า 3 ชนิด


## Tools and Language

- [CiRA Core](https://www.cira-ai.com)
- [Python 3.11](https://peps.python.org/pep-0664/)

## คณะผู้จัดทำ
**นักเรียน**

- นาย พชรพล รังษีสกรณ์ โรงเรียนเตรียมอุดมศึกษาน้อมเกล้า | [resume](https://www.canva.com/design/DAGQRmRADYo/LDTgpqz22y7C_ZNu4vbLBA/view?utm_content=DAGQRmRADYo&utm_campaign=designshare&utm_medium=link&utm_source=editor) 

- นาย พชรพล แหวนทองคำ โรงเรียนเตรียมอุดมศึกษาน้อมเกล้า

- นาย พีรวิชญ์ อารีพิทักษ์ โรงเรียนเตรียมอุดมศึกษาน้อมเกล้า

- นาย ชนพ สิริจำลองวงศ์ โรงเรียนเตรียมอุดมศึกษาน้อมเกล้า

**คุณครูที่ปรึกษา**
- นาย คมกริช อุดารักษ์ โรงเรียนเตรียมอุดมศึกษาน้อมเกล้า
