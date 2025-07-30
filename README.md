# Leny San Sushi - Restaurant Management System

[![Laravel](https://img.shields.io/badge/Laravel-11-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)](https://laravel.com)
[![Angular](https://img.shields.io/badge/Angular-19-DD0031?style=for-the-badge&logo=angular&logoColor=white)](https://angular.io)
[![MySQL](https://img.shields.io/badge/MySQL-8.0-4479A1?style=for-the-badge&logo=mysql&logoColor=white)](https://mysql.com)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://typescriptlang.org)

 **Sistema completo de gestión para restaurante** con pedidos en tiempo real, panel administrativo y soporte multi-sucursal. Modernizando la experiencia del cliente y optimizando operaciones.

---

## Screenshots

### Páginas Públicas
<img width="1570" height="1260" alt="image" src="https://github.com/user-attachments/assets/e981d917-f148-4ce0-b6be-c6e88b4cc02a" />
<img width="1485" height="1048" alt="Captura de pantalla 2025-07-30 201454" src="https://github.com/user-attachments/assets/075a1786-0f36-4800-b808-1088633e5290" />
<img width="1484" height="1047" alt="Captura de pantalla 2025-07-30 201504" src="https://github.com/user-attachments/assets/a962a475-b5b5-4923-9f50-93ac6c8e37b7" />
<img width="1483" height="1044" alt="image" src="https://github.com/user-attachments/assets/1f8ddc1c-286d-4a1f-aed0-425d71349487" />
<img width="1479" height="1046" alt="Captura de pantalla 2025-07-30 201230" src="https://github.com/user-attachments/assets/282bda68-1b09-49d8-b96b-a68db0fd3251" />
<img width="1480" height="1045" alt="Captura de pantalla 2025-07-30 201236" src="https://github.com/user-attachments/assets/445152c2-9ff9-42e7-a9fc-8e61d1752c45" />
<img width="1479" height="1044" alt="Captura de pantalla 2025-07-30 201241" src="https://github.com/user-attachments/assets/d57bb5e7-5188-4877-8b83-2d721148ad3b" />

### Menú Público
<img width="1570" height="1260" alt="image" src="https://github.com/user-attachments/assets/fb83c97d-cdcd-4032-aaea-d42ec47ed1c9" />

### Flujo de Pedidos Completo
<img width="1497" height="1047" alt="Captura de pantalla 2025-07-30 202856" src="https://github.com/user-attachments/assets/592fe98a-50f8-4a2f-901b-fc6907429739" />
<img width="1496" height="1043" alt="Captura de pantalla 2025-07-30 194747 - copia" src="https://github.com/user-attachments/assets/8bf63b3b-6720-491b-83fc-5d8897c001af" />
<img width="1500" height="1045" alt="Captura de pantalla 2025-07-30 195633" src="https://github.com/user-attachments/assets/c3a14452-488e-40f2-973b-90de278257c5" />
<img width="1499" height="1046" alt="Captura de pantalla 2025-07-30 200138" src="https://github.com/user-attachments/assets/3baa9a7a-51e5-432a-abd7-9de6ae640d97" />
<img width="1496" height="1045" alt="image" src="https://github.com/user-attachments/assets/40254e7e-c8c9-4822-aeea-8dd56b9c6a27" />
<img width="1493" height="1047" alt="Captura de pantalla 2025-07-30 200339" src="https://github.com/user-attachments/assets/8a2be53e-5b0c-4723-a6dd-1458b176b25c" />

### Panel Administrativo
<img width="1496" height="1044" alt="Captura de pantalla 2025-07-30 194420" src="https://github.com/user-attachments/assets/02e0a1e2-386b-4dde-bceb-4f20170b8f80" />
<img width="1500" height="1046" alt="Captura de pantalla 2025-07-30 200617" src="https://github.com/user-attachments/assets/580ec864-e207-4bcf-8727-066744d3b573" />
<img width="1497" height="1042" alt="Captura de pantalla 2025-07-30 194655" src="https://github.com/user-attachments/assets/70bae53c-f43e-4481-bf21-2c2bcacdff0d" />

### Mails
<table>
  <tr>
        <td><img width="1166" height="925" alt="Captura de pantalla 2025-07-30 200742" src="https://github.com/user-attachments/assets/55a3b364-5794-414a-a2d1-97085c6a102b" /></td>
        <td><img width="1232" height="945" alt="Captura de pantalla 2025-07-30 200828" src="https://github.com/user-attachments/assets/95230839-b3ef-420d-9157-ab210d214e49" /></td>
      <td><img width="1239" height="949" alt="Captura de pantalla 2025-07-30 200846" src="https://github.com/user-attachments/assets/a90c45cf-021a-4024-abc1-2cb046854024" /></td>
      <td><img width="1235" height="948" alt="Captura de pantalla 2025-07-30 200903" src="https://github.com/user-attachments/assets/540db0db-97c4-4780-962d-d06fdd4221ac" /></td>
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
