# Leny San Sushi - Restaurant Management System

[![Laravel](https://img.shields.io/badge/Laravel-11-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)](https://laravel.com)
[![Angular](https://img.shields.io/badge/Angular-19-DD0031?style=for-the-badge&logo=angular&logoColor=white)](https://angular.io)
[![MySQL](https://img.shields.io/badge/MySQL-8.0-4479A1?style=for-the-badge&logo=mysql&logoColor=white)](https://mysql.com)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://typescriptlang.org)

 **Sistema completo de gestión para restaurante** con pedidos en tiempo real, panel administrativo y soporte multi-sucursal. Modernizando la experiencia del cliente y optimizando operaciones.

---

## Screenshots

### Páginas Públicas
<img width="1570" height="1260" alt="image" src="img/image_1.png" />
<img width="1485" height="1048" alt="Captura de pantalla 2025-07-30 201454" src="img/image_2.png" />
<img width="1484" height="1047" alt="Captura de pantalla 2025-07-30 201504" src="img/image_3.png" />
<img width="1483" height="1044" alt="image" src="img/image_4.png" />
<img width="1479" height="1046" alt="Captura de pantalla 2025-07-30 201230" src="img/image_5.png" />
<img width="1480" height="1045" alt="Captura de pantalla 2025-07-30 201236" src="img/image_6.png" />
<img width="1479" height="1044" alt="Captura de pantalla 2025-07-30 201241" src="img/image_7.png" />

### Menú Público
<img width="1577" height="1264" alt="image" src="img/menu.png" />

### Flujo de Pedidos Completo
<img width="1497" height="1047" alt="Captura de pantalla 2025-07-30 202856" src="img/flujo_pedido_1.png" />
<img width="1496" height="1043" alt="Captura de pantalla 2025-07-30 194747 - copia" src="img/flujo_pedido_2.png" />
<img width="1500" height="1045" alt="Captura de pantalla 2025-07-30 195633" src="img/flujo_pedido_3.png" />
<img width="1499" height="1046" alt="Captura de pantalla 2025-07-30 200138" src="img/flujo_pedido_4.png" />
<img width="1496" height="1045" alt="image" src="img/flujo_pedido_5.png" />
<img width="1493" height="1047" alt="Captura de pantalla 2025-07-30 200339" src="img/flujo_pedido_6.png" />

### Panel Administrativo
<img width="1496" height="1044" alt="Captura de pantalla 2025-07-30 194420" src="img/admin_1.png" />
<img width="1500" height="1046" alt="Captura de pantalla 2025-07-30 200617" src="img/admin_2.png" />
<img width="1497" height="1042" alt="Captura de pantalla 2025-07-30 194655" src="img/admin_3.png" />

### Mails
<table>
  <tr>
        <td><img width="1166" height="925" alt="Captura de pantalla 2025-07-30 200742" src="img/mail_1.png" /></td>
        <td><img width="1232" height="945" alt="Captura de pantalla 2025-07-30 200828" src="img/mail_2.png" /></td>
      <td><img width="1239" height="949" alt="Captura de pantalla 2025-07-30 200846" src="img/mail_3.png" /></td>
      <td><img width="1235" height="948" alt="Captura de pantalla 2025-07-30 200903" src="img/mail_4.png" /></td>
  </tr>
</table>


---

<details>
<summary>📋 <strong>Problema de Negocio & Solución</strong></summary>

### 🎯 Problemas Identificados
- **Gestión Manual Ineficiente**: Cartas físicas desactualizadas, cambios de precios requieren reimpresión
- **Sistema de Pedidos Obsoleto**: Dependencia de llamadas telefónicas con errores frecuentes
- **Falta de Trazabilidad**: Sin seguimiento digital del estado de pedidos
- **Saturación Operativa**: Líneas telefónicas ocupadas = pérdida de ventas

### ✅ Solución Implementada
- **🏪 Gestión Digital**: Panel admin para actualizar menú, precios y disponibilidad en tiempo real
- **📱 Pedidos Automatizados**: Sistema web completo con validación geográfica de delivery
- **🔔 Notificaciones Tiempo Real**: SSE para alertas instantáneas a cocina y administración
- **📊 Dashboard Unificado**: Seguimiento completo desde "En Espera" hasta "Completado"
- **🌍 Multi-Sucursal**: Control independiente de operaciones AR/US

</details>

---

## 🛠️ Stack Técnico

<table>
<tr>
<td width="50%">

### Frontend
- **Framework**: Angular 19 (Standalone Components)
- **UI/UX**: Angular Material + SCSS
- **State**: RxJS Observables
- **Maps**: Google Maps, LocationIQ, Leaflet
- **i18n**: ngx-translate

</td>
<td width="50%">

### Backend
- **Framework**: Laravel 11 + Sanctum Auth
- **Database**: MySQL + Eloquent ORM
- **API**: RESTful + Resource Controllers
- **Real-time**: Server-Sent Events (SSE)
- **Payment**: Stripe Integration

</td>
</tr>
</table>

---

## 🏗️ Arquitectura del Sistema

### 📊 Flujo de Estados de Órdenes
```mermaid
graph LR
    A[EN_ESPERA] --> B[EN_PREPARACION]
    B --> C[A_ENTREGAR]
    C --> D[COMPLETADO]
    A --> E[CANCELADO]
    B --> E
    C --> E
```

## 🔧 Características Principales

### 🛒 **Sistema de Pedidos Completo**
- Selección delivery/pickup con validación geográfica
- Carrito persistente
- Checkout protegido con autenticación

### 🔔 **Notificaciones en Tiempo Real**
- Server-Sent Events (SSE) para updates instantáneos
- Dashboard administrativo con alertas
- Seguimiento de estados automático

### 🌍 **Multi-Sucursal (AR/US)**
- Control independiente por región
- Configuración específica de delivery y horarios

### 📊 **Panel Administrativo**
- Gestión de menú con sistema de backup
- Dashboard de órdenes en tiempo real
- Configuración de restaurante por sucursal
