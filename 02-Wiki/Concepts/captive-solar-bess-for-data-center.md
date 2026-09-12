---
title: "Captive Solar + BESS สำหรับ Data Center"
type: concept
archetype: "structural-shift"
status: draft
created: 2026-09-11
updated: 2026-09-11
sources:
  - "[[02-Wiki/Sources/20260911-STPI-set-daisy-drive-55mw-solar]]"
  - "[[02-Wiki/Sources/20250113-STPI-ir-press-eec-captive-solar-farm]]"
confidence: medium
verification: pending
tags: [solar, BESS, data-center, captive-power, JCM, EEC]
---

# Definition

การสร้างโรงไฟฟ้าโซลาร์พร้อมระบบกักเก็บ (BESS) เพื่อจ่ายหรือสนับสนุนไฟฟ้าให้โหลด **Data Center** โดยตรง (หรือใกล้เคียงการใช้แบบ captive) แทนการพึ่งพาเฉพาะกริดทั่วไป กลไกสำคัญคือจับคู่ความต้องการไฟฟ้าที่ต่อเนื่องของศูนย์ข้อมูลกับกำลังผลิตหมุนเวียนที่มีความผันผวน โดยใช้ BESS ช่วยปรับช่วงเวลาจ่ายไฟ และอาจดึงเงินสนับสนุนคาร์บอน/เครดิตข้ามประเทศ (เช่น JCM) มาลดต้นทุนโครงสร้าง

## Investor Implication

- **Capital Allocation:** เงินลงทุนโครงการสูงเมื่อเทียบกับเงินซื้อหุ้นเริ่มต้น — ต้องแยก “ค่าหุ้นที่เป็นบริษัทย่อย” กับ “ภาระทุนโครงการ” ให้ชัด
- **Unit economics:** ขึ้นกับสัญญาขายไฟ/การใช้ภายใน, สัดส่วนหนี้, และเงื่อนไขเงินสนับสนุน; ยังไม่มี tariff ในแหล่งต้นทางนี้
- **Risk stack:** ความเสี่ยงโครงการ (COD, กู้, JCM) ทับความเสี่ยงลูกค้า Data Center

## Value Chain & Second-Order Effects

- **Primary Beneficiaries:** ผู้พัฒนา solar+BESS ที่เข้าถึงโหลด Data Center และแหล่งทุนสีเขียว; เจ้าของศูนย์ข้อมูลที่ต้องการไฟฟ้าสะอาด/เสถียร
- **Disrupted / Negative Exposure:** ซัพพลายไฟฟ้าทั่วไปที่แข่งด้วยราคาอย่างเดียวหากลูกค้าย้ายไป captive หรือสัญญาเฉพาะราย

## Leading Indicators to Track

- ขนาด MW / MWh ที่ประกาศจริงและ COD
- สัดส่วน equity vs debt vs grant (JCM หรือเทียบเท่า)
- ชื่อลูกค้า/ทำเล Data Center และรูปแบบสัญญา
- สัดส่วนถือครองและ consolidation เข้างบบริษัทแม่

## Boundaries & Falsification Criteria

- **When it applies:** มีโหลด Data Center ที่ระบุได้ และโครงการ solar+BESS ถูกออกแบบรองรับโหลดนั้น
- **When it does NOT apply:** ประกาศ solar ทั่วไปโดยไม่ผูกโหลดศูนย์ข้อมูล หรือ BESS เป็นแค่ option ในอนาคต
- **Falsification Criteria:** โครงการยกเลิก/ลดขนาด, ไม่มีสัญญาหรือการใช้จริงกับ Data Center, หรือเงินสนับสนุน/เงินกู้ไม่ปิดได้จนทุนโครงการค้าง

## Concrete Example

STPI ผ่าน ISGT เข้าถือ Daisy Drive 60% สำหรับแผน Solar 55 MW + BESS 40 MWh เพื่อสนับสนุนพลังงานสะอาดให้โครงการ Data Center มูลค่าโครงการประมาณ 1,419 ล้านบาท โดยมี JCM ในโครงสร้างเงินทุน ([[02-Wiki/Sources/20260911-STPI-set-daisy-drive-55mw-solar]])

ข่าว IR ม.ค. 2025 ของ STPI (น้ำหนักต่ำกว่า SET) อธิบายวิทยาเขต data center ใน EEC พร้อม **captive solar farm** คู่โครงสร้างไฟฟ้า — ไม่ระบุ MW ของ captive farm และไม่พูด BESS ([[02-Wiki/Sources/20250113-STPI-ir-press-eec-captive-solar-farm]])

## Sources

- [[02-Wiki/Sources/20260911-STPI-set-daisy-drive-55mw-solar]]
- [[02-Wiki/Sources/20250113-STPI-ir-press-eec-captive-solar-farm]]
