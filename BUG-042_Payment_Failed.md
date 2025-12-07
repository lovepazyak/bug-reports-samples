# BUG-042 — Платёж прошёл, но статус остался "Pending"

**Severity**: Critical  
**Priority**: High  
**Environment**: Chrome 129, iOS 17  
**Steps to reproduce**:  
1. Оплатить заказ на 5000 тг картой Visa  
2. 3D-Secure пройден успешно  
3. Вернуться в приложение  

**Actual**: Статус заказа "Pending", деньги списаны  
**Expected**: Статус "Paid"  
