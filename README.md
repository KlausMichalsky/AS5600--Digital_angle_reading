# AS5600--Digital_angle_reading
### Lectura de ángulo digital desde sensor AS5600 (salida I2C)
  - Lee el ángulo del sensor AS5600 conectado a GP26 (SDA) y GP27 (SCL) usando I2C.
  - Convierte el valor crudo de 12 bits (0–4095) a grados (0°–360°).
  - Muestra el ángulo por Serial cada 200 ms.
  - Usa Wire1 para I2C independiente de los pines por defecto.
