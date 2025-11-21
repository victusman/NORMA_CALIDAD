# NORMA FBD-2025-001: ESTÁNDAR DE CALIDAD DE SOFTWARE PARA SISTEMA FÁBRICA BIODEGRADABLE

---

<div style="display: grid; grid-template-columns: repeat(4, 1fr); gap: 15px; margin: 25px 0;">

<div style="border: 4px solid #1976d2; border-radius: 15px; padding: 18px; background: linear-gradient(135deg, #e3f2fd 0%, #bbdefb 100%); text-align: center; box-shadow: 0 6px 12px rgba(0,0,0,0.15);">
<h3 style="color: #0d47a1; margin: 0 0 12px 0; font-size: 16px;">📋 IDENTIFICACIÓN</h3>
<div style="background: white; padding: 12px; border-radius: 8px; font-size: 14px; font-weight: bold;">
<span style="color: #1976d2;">Código:</span> FBD-2025-001<br>
<span style="color: #1976d2;">Versión:</span> 1.0<br>
<span style="color: #1976d2;">Estado:</span> Vigente
</div>
</div>

<div style="border: 4px solid #388e3c; border-radius: 15px; padding: 18px; background: linear-gradient(135deg, #e8f5e8 0%, #c8e6c9 100%); text-align: center; box-shadow: 0 6px 12px rgba(0,0,0,0.15);">
<h3 style="color: #1b5e20; margin: 0 0 12px 0; font-size: 16px;">📅 TEMPORAL</h3>
<div style="background: white; padding: 12px; border-radius: 8px; font-size: 14px; font-weight: bold;">
<span style="color: #388e3c;">Creación:</span> 21 Nov 2025<br>
<span style="color: #388e3c;">Vigencia:</span> Inmediata<br>
<span style="color: #388e3c;">Revisión:</span> Trimestral
</div>
</div>

<div style="border: 4px solid #f57c00; border-radius: 15px; padding: 18px; background: linear-gradient(135deg, #fff3e0 0%, #ffcc80 100%); text-align: center; box-shadow: 0 6px 12px rgba(0,0,0,0.15);">
<h3 style="color: #e65100; margin: 0 0 12px 0; font-size: 16px;">🏢 ORGANIZACIONAL</h3>
<div style="background: white; padding: 12px; border-radius: 8px; font-size: 14px; font-weight: bold;">
<span style="color: #f57c00;">Proyecto:</span> Fábrica Biodegradable<br>
<span style="color: #f57c00;">Empresa:</span> EcoPlast Industrial<br>
<span style="color: #f57c00;">Área:</span> Desarrollo Software
</div>
</div>

<div style="border: 4px solid #7b1fa2; border-radius: 15px; padding: 18px; background: linear-gradient(135deg, #f3e5f5 0%, #e1bee7 100%); text-align: center; box-shadow: 0 6px 12px rgba(0,0,0,0.15);">
<h3 style="color: #4a148c; margin: 0 0 12px 0; font-size: 16px;">⚙️ TECNOLÓGICO</h3>
<div style="background: white; padding: 12px; border-radius: 8px; font-size: 14px; font-weight: bold;">
<span style="color: #7b1fa2;">Backend:</span> Laravel 12<br>
<span style="color: #7b1fa2;">Frontend:</span> Vue.js 3<br>
<span style="color: #7b1fa2;">DB:</span> MySQL + Redis
</div>
</div>

</div>

---

## 1. OBJETO Y CAMPO DE APLICACIÓN

### 1.1 Objeto Principal

<div style="border: 4px solid #d32f2f; border-radius: 15px; padding: 20px; background: linear-gradient(135deg, #ffebee 0%, #ffcdd2 100%); margin: 20px 0; box-shadow: 0 6px 12px rgba(0,0,0,0.15);">
<h3 style="color: #b71c1c; margin: 0 0 15px 0; text-align: center;">🎯 PROPÓSITO ESPECÍFICO</h3>
<div style="background: white; padding: 15px; border-radius: 10px; font-size: 15px; line-height: 1.6; text-align: justify;">
<strong>Establecer los estándares de calidad específicos para el desarrollo del Sistema de Monitoreo Industrial de Fábrica Biodegradable</strong>, definiendo procesos, metodologías y criterios de aceptación que garanticen la excelencia en el desarrollo de software para entornos de producción de materiales biodegradables, siguiendo las mejores prácticas de las normas IEEE e ISO adaptadas al contexto del proyecto.
</div>
</div>

### 1.2 Alcance Funcional y Técnico

<div style="display: grid; grid-template-columns: 1fr 1fr; gap: 20px; margin: 25px 0;">

<div style="border: 4px solid #2e7d32; border-radius: 15px; padding: 20px; background: linear-gradient(135deg, #e8f5e8 0%, #a5d6a7 100%); box-shadow: 0 6px 12px rgba(0,0,0,0.15);">
<h3 style="color: #1b5e20; margin: 0 0 15px 0; text-align: center;">✅ INCLUYE</h3>
<div style="display: grid; gap: 10px;">

<div style="background: white; padding: 12px; border-radius: 8px; border-left: 4px solid #4caf50;">
<strong style="color: #2e7d32;">🔧 Desarrollo de Software</strong><br>
<span style="font-size: 13px;">Backend Laravel, Frontend Vue.js, APIs RESTful</span>
</div>

<div style="background: white; padding: 12px; border-radius: 8px; border-left: 4px solid #4caf50;">
<strong style="color: #2e7d32;">🏭 Sistema de Monitoreo</strong><br>
<span style="font-size: 13px;">Máquinas, producción, materias primas biodegradables</span>
</div>

<div style="background: white; padding: 12px; border-radius: 8px; border-left: 4px solid #4caf50;">
<strong style="color: #2e7d32;">📊 Dashboard en Tiempo Real</strong><br>
<span style="font-size: 13px;">Visualización, alertas, reportes, WebSockets</span>
</div>

<div style="background: white; padding: 12px; border-radius: 8px; border-left: 4px solid #4caf50;">
<strong style="color: #2e7d32;">🧪 Testing y QA</strong><br>
<span style="font-size: 13px;">Unitarias, integración, funcionales, rendimiento</span>
</div>

<div style="background: white; padding: 12px; border-radius: 8px; border-left: 4px solid #4caf50;">
<strong style="color: #2e7d32;">📱 Interfaz Responsiva</strong><br>
<span style="font-size: 13px;">Múltiples dispositivos y navegadores</span>
</div>

</div>
</div>

<div style="border: 4px solid #c62828; border-radius: 15px; padding: 20px; background: linear-gradient(135deg, #ffebee 0%, #ef9a9a 100%); box-shadow: 0 6px 12px rgba(0,0,0,0.15);">
<h3 style="color: #b71c1c; margin: 0 0 15px 0; text-align: center;">❌ EXCLUYE</h3>
<div style="display: grid; gap: 10px;">

<div style="background: white; padding: 12px; border-radius: 8px; border-left: 4px solid #f44336;">
<strong style="color: #c62828;">⚙️ Hardware Industrial</strong><br>
<span style="font-size: 13px;">Sensores, PLCs, equipos de producción física</span>
</div>

<div style="background: white; padding: 12px; border-radius: 8px; border-left: 4px solid #f44336;">
<strong style="color: #c62828;">🌐 Infraestructura de Red</strong><br>
<span style="font-size: 13px;">Configuración de redes, routers, switches</span>
</div>

<div style="background: white; padding: 12px; border-radius: 8px; border-left: 4px solid #f44336;">
<strong style="color: #c62828;">🏭 Procesos de Manufactura</strong><br>
<span style="font-size: 13px;">Química de biodegradables, formulaciones</span>
</div>

<div style="background: white; padding: 12px; border-radius: 8px; border-left: 4px solid #f44336;">
<strong style="color: #c62828;">👥 Capacitación Operativa</strong><br>
<span style="font-size: 13px;">Entrenamiento de operarios de planta</span>
</div>

<div style="background: white; padding: 12px; border-radius: 8px; border-left: 4px solid #f44336;">
<strong>🔧 Mantenimiento Físico</strong><br>
<span style="font-size: 13px;">Calibración y reparación de equipos</span>
</div>

</div>
</div>

</div>

---

## 2. ARQUITECTURA TÉCNICA ESPECÍFICA DEL PROYECTO

### 2.1 Stack Tecnológico Implementado

<div style="display: grid; grid-template-columns: repeat(4, 1fr); gap: 15px; margin: 25px 0;">

<div style="border: 4px solid #e91e63; border-radius: 12px; padding: 15px; background: linear-gradient(135deg, #fce4ec 0%, #f48fb1 100%); text-align: center; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
<h4 style="color: #ad1457; margin: 0 0 10px 0;">🎨 FRONTEND</h4>
<div style="display: grid; gap: 6px;">
<div style="background: white; padding: 8px; border-radius: 6px; font-size: 12px; border-left: 3px solid #e91e63;">
<strong>Vue.js 3</strong><br>Framework SPA
</div>
<div style="background: white; padding: 8px; border-radius: 6px; font-size: 12px; border-left: 3px solid #e91e63;">
<strong>Inertia.js</strong><br>Backend Bridge
</div>
<div style="background: white; padding: 8px; border-radius: 6px; font-size: 12px; border-left: 3px solid #e91e63;">
<strong>Tailwind CSS</strong><br>Styling System
</div>
</div>
</div>

<div style="border: 4px solid #3f51b5; border-radius: 12px; padding: 15px; background: linear-gradient(135deg, #e8eaf6 0%, #9fa8da 100%); text-align: center; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
<h4 style="color: #303f9f; margin: 0 0 10px 0;">⚙️ BACKEND</h4>
<div style="display: grid; gap: 6px;">
<div style="background: white; padding: 8px; border-radius: 6px; font-size: 12px; border-left: 3px solid #3f51b5;">
<strong>Laravel 12</strong><br>PHP Framework
</div>
<div style="background: white; padding: 8px; border-radius: 6px; font-size: 12px; border-left: 3px solid #3f51b5;">
<strong>Eloquent ORM</strong><br>Database Layer
</div>
<div style="background: white; padding: 8px; border-radius: 6px; font-size: 12px; border-left: 3px solid #3f51b5;">
<strong>Laravel Reverb</strong><br>WebSocket Server
</div>
</div>
</div>

<div style="border: 4px solid #009688; border-radius: 12px; padding: 15px; background: linear-gradient(135deg, #e0f2f1 0%, #80cbc4 100%); text-align: center; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
<h4 style="color: #00695c; margin: 0 0 10px 0;">💾 DATOS</h4>
<div style="display: grid; gap: 6px;">
<div style="background: white; padding: 8px; border-radius: 6px; font-size: 12px; border-left: 3px solid #009688;">
<strong>MySQL 8.0</strong><br>Database Primary
</div>
<div style="background: white; padding: 8px; border-radius: 6px; font-size: 12px; border-left: 3px solid #009688;">
<strong>Redis</strong><br>Cache & Sessions
</div>
<div style="background: white; padding: 8px; border-radius: 6px; font-size: 12px; border-left: 3px solid #009688;">
<strong>Migrations</strong><br>Schema Control
</div>
</div>
</div>

<div style="border: 4px solid #ff5722; border-radius: 12px; padding: 15px; background: linear-gradient(135deg, #fbe9e7 0%, #ffab91 100%); text-align: center; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
<h4 style="color: #d84315; margin: 0 0 10px 0;">🔧 TOOLS</h4>
<div style="display: grid; gap: 6px;">
<div style="background: white; padding: 8px; border-radius: 6px; font-size: 12px; border-left: 3px solid #ff5722;">
<strong>Vite</strong><br>Build System
</div>
<div style="background: white; padding: 8px; border-radius: 6px; font-size: 12px; border-left: 3px solid #ff5722;">
<strong>PHPUnit</strong><br>Testing Backend
</div>
<div style="background: white; padding: 8px; border-radius: 6px; font-size: 12px; border-left: 3px solid #ff5722;">
<strong>Composer</strong><br>Dependencies
</div>
</div>
</div>

</div>

---

## 4. TÉRMINOS Y DEFINICIONES ESPECÍFICAS

### 4.1 Terminología del Dominio Industrial

<div style="display: grid; grid-template-columns: repeat(3, 1fr); gap: 15px; margin: 25px 0;">

<div style="border: 4px solid #4caf50; border-radius: 15px; padding: 18px; background: linear-gradient(135deg, #e8f5e8 0%, #a5d6a7 100%); box-shadow: 0 6px 12px rgba(0,0,0,0.15);">
<h3 style="color: #1b5e20; margin: 0 0 15px 0; text-align: center;">🏭 TÉRMINOS INDUSTRIALES</h3>
<div style="display: grid; gap: 8px;">

<div style="background: white; padding: 10px; border-radius: 6px; border-left: 3px solid #4caf50;">
<strong style="color: #2e7d32;">OEE (Overall Equipment Effectiveness)</strong><br>
<span style="font-size: 12px;">Métrica de eficiencia operacional global de máquinas</span>
</div>

<div style="background: white; padding: 10px; border-radius: 6px; border-left: 3px solid #4caf50;">
<strong style="color: #2e7d32;">Dashboard Industrial</strong><br>
<span style="font-size: 12px;">Interfaz centralizada para monitoreo en tiempo real</span>
</div>

<div style="background: white; padding: 10px; border-radius: 6px; border-left: 3px solid #4caf50;">
<strong style="color: #2e7d32;">Sistema Crítico</strong><br>
<span style="font-size: 12px;">Sistema cuya falla implica pérdidas significativas</span>
</div>

<div style="background: white; padding: 10px; border-radius: 6px; border-left: 3px solid #4caf50;">
<strong style="color: #2e7d32;">Tiempo Real Industrial</strong><br>
<span style="font-size: 12px;">Respuesta inmediata del sistema para datos críticos</span>
</div>

</div>
</div>

<div style="border: 4px solid #2196f3; border-radius: 15px; padding: 18px; background: linear-gradient(135deg, #e3f2fd 0%, #90caf9 100%); box-shadow: 0 6px 12px rgba(0,0,0,0.15);">
<h3 style="color: #0d47a1; margin: 0 0 15px 0; text-align: center;">💻 TÉRMINOS TÉCNICOS</h3>
<div style="display: grid; gap: 8px;">

<div style="background: white; padding: 10px; border-radius: 6px; border-left: 3px solid #2196f3;">
<strong style="color: #1976d2;">SPA (Single Page Application)</strong><br>
<span style="font-size: 12px;">Aplicación web que carga una sola página HTML</span>
</div>

<div style="background: white; padding: 10px; border-radius: 6px; border-left: 3px solid #2196f3;">
<strong style="color: #1976d2;">API RESTful</strong><br>
<span style="font-size: 12px;">Interfaz de programación siguiendo principios REST</span>
</div>

<div style="background: white; padding: 10px; border-radius: 6px; border-left: 3px solid #2196f3;">
<strong style="color: #1976d2;">WebSocket</strong><br>
<span style="font-size: 12px;">Protocolo comunicación bidireccional tiempo real</span>
</div>

<div style="background: white; padding: 10px; border-radius: 6px; border-left: 3px solid #2196f3;">
<strong style="color: #1976d2;">Eloquent ORM</strong><br>
<span style="font-size: 12px;">Mapeo objeto-relacional ActiveRecord de Laravel</span>
</div>

</div>
</div>

<div style="border: 4px solid #ff5722; border-radius: 15px; padding: 18px; background: linear-gradient(135deg, #fbe9e7 0%, #ffab91 100%); box-shadow: 0 6px 12px rgba(0,0,0,0.15);">
<h3 style="color: #bf360c; margin: 0 0 15px 0; text-align: center;">🔍 TÉRMINOS CALIDAD</h3>
<div style="display: grid; gap: 8px;">

<div style="background: white; padding: 10px; border-radius: 6px; border-left: 3px solid #ff5722;">
<strong style="color: #d84315;">Defecto Crítico</strong><br>
<span style="font-size: 12px;">Impide funcionamiento del sistema completamente</span>
</div>

<div style="background: white; padding: 10px; border-radius: 6px; border-left: 3px solid #ff5722;">
<strong style="color: #d84315;">Defecto Mayor</strong><br>
<span style="font-size: 12px;">Afecta funcionalidad principal pero no bloquea</span>
</div>

<div style="background: white; padding: 10px; border-radius: 6px; border-left: 3px solid #ff5722;">
<strong style="color: #d84315;">Defecto Menor</strong><br>
<span style="font-size: 12px;">No afecta funcionalidad core, solo UX</span>
</div>

<div style="background: white; padding: 10px; border-radius: 6px; border-left: 3px solid #ff5722;">
<strong style="color: #d84315;">Cobertura de Código</strong><br>
<span style="font-size: 12px;">Porcentaje de código ejecutado durante testing</span>
</div>

</div>
</div>

</div>

### 4.2 Definiciones Específicas del Proyecto

<div style="border: 4px solid #9c27b0; border-radius: 15px; padding: 20px; background: linear-gradient(135deg, #f3e5f5 0%, #ce93d8 100%); margin: 20px 0; box-shadow: 0 6px 12px rgba(0,0,0,0.15);">
<h3 style="color: #4a148c; margin: 0 0 15px 0; text-align: center;">🧬 TÉRMINOS BIODEGRADABLES ESPECÍFICOS</h3>
<div style="display: grid; grid-template-columns: 1fr 1fr; gap: 15px;">

<div style="background: white; padding: 15px; border-radius: 10px;">
<h4 style="color: #7b1fa2; margin: 0 0 10px 0;">📦 Gestión de Materiales</h4>
<div style="font-size: 13px; line-height: 1.5;">
• <strong>Materia Prima Biodegradable:</strong> Insumos orgánicos/sintéticos degradables<br>
• <strong>Lote de Materia Prima:</strong> Agrupación trazable de insumos<br>
• <strong>Receta de Producto:</strong> Formulación específica biodegradable<br>
• <strong>Trazabilidad:</strong> Seguimiento completo origen-destino
</div>
</div>

<div style="background: white; padding: 15px; border-radius: 10px;">
<h4 style="color: #7b1fa2; margin: 0 0 10px 0;">⚙️ Procesos de Producción</h4>
<div style="font-size: 13px; line-height: 1.5;">
• <strong>Orden de Producción:</strong> Instrucción fabricación específica<br>
• <strong>Consumo de Producción:</strong> Materiales utilizados proceso<br>
• <strong>Estado de Máquina:</strong> Operativa/Parada/Mantenimiento<br>
• <strong>Parada Planificada:</strong> Detención programada producción
</div>
</div>

</div>
</div>

---

## 5. REQUISITOS DEL SISTEMA

### 5.1 Requisitos Funcionales Específicos

<div style="display: grid; grid-template-columns: 1fr 1fr; gap: 20px; margin: 25px 0;">

<div style="border: 4px solid #3f51b5; border-radius: 15px; padding: 20px; background: linear-gradient(135deg, #e8eaf6 0%, #9fa8da 100%); box-shadow: 0 6px 12px rgba(0,0,0,0.15);">
<h3 style="color: #1a237e; margin: 0 0 15px 0; text-align: center;">📊 DASHBOARD Y MONITOREO</h3>
<div style="display: grid; gap: 10px;">

<div style="background: white; padding: 12px; border-radius: 8px; border-left: 4px solid #3f51b5;">
<strong style="color: #303f9f;">RF-001: Dashboard Principal</strong><br>
<span style="font-size: 12px;">Visualización tiempo real estado todas las máquinas</span>
</div>

<div style="background: white; padding: 12px; border-radius: 8px; border-left: 4px solid #3f51b5;">
<strong style="color: #303f9f;">RF-002: Indicadores Visuales</strong><br>
<span style="font-size: 12px;">Código colores: Verde/Amarillo/Rojo estados operacionales</span>
</div>

<div style="background: white; padding: 12px; border-radius: 8px; border-left: 4px solid #3f51b5;">
<strong style="color: #303f9f;">RF-003: Métricas en Tiempo Real</strong><br>
<span style="font-size: 12px;">OEE, producción actual, eficiencia por máquina</span>
</div>

<div style="background: white; padding: 12px; border-radius: 8px; border-left: 4px solid #3f51b5;">
<strong style="color: #303f9f;">RF-004: Filtros Avanzados</strong><br>
<span style="font-size: 12px;">Por línea producción, fecha, tipo evento, máquina</span>
</div>

</div>
</div>

<div style="border: 4px solid #f44336; border-radius: 15px; padding: 20px; background: linear-gradient(135deg, #ffebee 0%, #ef9a9a 100%); box-shadow: 0 6px 12px rgba(0,0,0,0.15);">
<h3 style="color: #b71c1c; margin: 0 0 15px 0; text-align: center;">🚨 SISTEMA DE ALERTAS</h3>
<div style="display: grid; gap: 10px;">

<div style="background: white; padding: 12px; border-radius: 8px; border-left: 4px solid #f44336;">
<strong style="color: #c62828;">RF-005: Alertas Automáticas</strong><br>
<span style="font-size: 12px;">Notificaciones inmediatas eventos críticos</span>
</div>

<div style="background: white; padding: 12px; border-radius: 8px; border-left: 4px solid #f44336;">
<strong style="color: #c62828;">RF-006: Escalamiento</strong><br>
<span style="font-size: 12px;">Niveles alerta según severidad y tiempo respuesta</span>
</div>

<div style="background: white; padding: 12px; border-radius: 8px; border-left: 4px solid #f44336;">
<strong style="color: #c62828;">RF-007: Configuración Umbrales</strong><br>
<span style="font-size: 12px;">Personalización límites por tipo máquina</span>
</div>

<div style="background: white; padding: 12px; border-radius: 8px; border-left: 4px solid #f44336;">
<strong style="color: #c62828;">RF-008: Histórico Alertas</strong><br>
<span style="font-size: 12px;">Registro completo eventos con timestamps</span>
</div>

</div>
</div>

<div style="border: 4px solid #009688; border-radius: 15px; padding: 20px; background: linear-gradient(135deg, #e0f2f1 0%, #80cbc4 100%); box-shadow: 0 6px 12px rgba(0,0,0,0.15);">
<h3 style="color: #004d40; margin: 0 0 15px 0; text-align: center;">💾 GESTIÓN DE DATOS</h3>
<div style="display: grid; gap: 10px;">

<div style="background: white; padding: 12px; border-radius: 8px; border-left: 4px solid #009688;">
<strong style="color: #00695c;">RF-009: Almacenamiento Seguro</strong><br>
<span style="font-size: 12px;">Datos históricos producción con backup automático</span>
</div>

<div style="background: white; padding: 12px; border-radius: 8px; border-left: 4px solid #009688;">
<strong style="color: #00695c;">RF-010: Integridad Referencial</strong><br>
<span style="font-size: 12px;">Consistencia entre todas las entidades relacionadas</span>
</div>

<div style="background: white; padding: 12px; border-radius: 8px; border-left: 4px solid #009688;">
<strong style="color: #00695c;">RF-011: Trazabilidad Completa</strong><br>
<span style="font-size: 12px;">Seguimiento cambios configuración y auditoría</span>
</div>

<div style="background: white; padding: 12px; border-radius: 8px; border-left: 4px solid #009688;">
<strong style="color: #00695c;">RF-012: APIs RESTful</strong><br>
<span style="font-size: 12px;">Interfaces estándar para integración externa</span>
</div>

</div>
</div>

<div style="border: 4px solid #ff9800; border-radius: 15px; padding: 20px; background: linear-gradient(135deg, #fff3e0 0%, #ffb74d 100%); box-shadow: 0 6px 12px rgba(0,0,0,0.15);">
<h3 style="color: #e65100; margin: 0 0 15px 0; text-align: center;">📊 REPORTES Y ANÁLISIS</h3>
<div style="display: grid; gap: 10px;">

<div style="background: white; padding: 12px; border-radius: 8px; border-left: 4px solid #ff9800;">
<strong style="color: #f57c00;">RF-013: Reportes Automáticos</strong><br>
<span style="font-size: 12px;">Generación programada reportes producción</span>
</div>

<div style="background: white; padding: 12px; border-radius: 8px; border-left: 4px solid #ff9800;">
<strong style="color: #f57c00;">RF-014: Exportación Datos</strong><br>
<span style="font-size: 12px;">Formatos PDF, Excel, CSV para análisis externo</span>
</div>

<div style="background: white; padding: 12px; border-radius: 8px; border-left: 4px solid #ff9800;">
<strong style="color: #f57c00;">RF-015: Gráficos Tendencias</strong><br>
<span style="font-size: 12px;">Visualización histórica métricas clave</span>
</div>

<div style="background: white; padding: 12px; border-radius: 8px; border-left: 4px solid #ff9800;">
<strong style="color: #f57c00;">RF-016: KPIs Personalizados</strong><br>
<span style="font-size: 12px;">Métricas específicas biodegradables configurables</span>
</div>

</div>
</div>

</div>

### 5.2 Requisitos No Funcionales Cuantificados

<div style="display: grid; grid-template-columns: repeat(4, 1fr); gap: 15px; margin: 25px 0;">

<div style="border: 4px solid #e91e63; border-radius: 12px; padding: 15px; background: linear-gradient(135deg, #fce4ec 0%, #f48fb1 100%); text-align: center; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
<h4 style="color: #ad1457; margin: 0 0 10px 0;">🚀 RENDIMIENTO</h4>
<div style="display: grid; gap: 6px;">
<div style="background: white; padding: 8px; border-radius: 6px; font-size: 11px; border-left: 3px solid #e91e63;">
<strong>Tiempo Carga:</strong> Rápido
</div>
<div style="background: white; padding: 8px; border-radius: 6px; font-size: 11px; border-left: 3px solid #e91e63;">
<strong>Respuesta API:</strong> Óptima
</div>
<div style="background: white; padding: 8px; border-radius: 6px; font-size: 11px; border-left: 3px solid #e91e63;">
<strong>Usuarios Concurrentes:</strong> Múltiples
</div>
<div style="background: white; padding: 8px; border-radius: 6px; font-size: 11px; border-left: 3px solid #e91e63;">
<strong>Actualizaciones RT:</strong> Inmediatas
</div>
</div>
</div>

<div style="border: 4px solid #673ab7; border-radius: 12px; padding: 15px; background: linear-gradient(135deg, #ede7f6 0%, #b39ddb 100%); text-align: center; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
<h4 style="color: #4527a0; margin: 0 0 10px 0;">🔒 SEGURIDAD</h4>
<div style="display: grid; gap: 6px;">
<div style="background: white; padding: 8px; border-radius: 6px; font-size: 11px; border-left: 3px solid #673ab7;">
<strong>Autenticación:</strong> Multifactor
</div>
<div style="background: white; padding: 8px; border-radius: 6px; font-size: 11px; border-left: 3px solid #673ab7;">
<strong>Cifrado:</strong> Alto nivel
</div>
<div style="background: white; padding: 8px; border-radius: 6px; font-size: 11px; border-left: 3px solid #673ab7;">
<strong>Sesiones:</strong> Timeout automático
</div>
<div style="background: white; padding: 8px; border-radius: 6px; font-size: 11px; border-left: 3px solid #673ab7;">
<strong>Auditoría:</strong> Completa
</div>
</div>
</div>

<div style="border: 4px solid #4caf50; border-radius: 12px; padding: 15px; background: linear-gradient(135deg, #e8f5e8 0%, #a5d6a7 100%); text-align: center; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
<h4 style="color: #2e7d32; margin: 0 0 10px 0;">🔄 DISPONIBILIDAD</h4>
<div style="display: grid; gap: 6px;">
<div style="background: white; padding: 8px; border-radius: 6px; font-size: 11px; border-left: 3px solid #4caf50;">
<strong>Uptime:</strong> Alta disponibilidad
</div>
<div style="background: white; padding: 8px; border-radius: 6px; font-size: 11px; border-left: 3px solid #4caf50;">
<strong>Recuperación:</strong> Rápida
</div>
<div style="background: white; padding: 8px; border-radius: 6px; font-size: 11px; border-left: 3px solid #4caf50;">
<strong>Datos:</strong> Protegidos
</div>
<div style="background: white; padding: 8px; border-radius: 6px; font-size: 11px; border-left: 3px solid #4caf50;">
<strong>Backup:</strong> Automático frecuente
</div>
</div>
</div>

<div style="border: 4px solid #795548; border-radius: 12px; padding: 15px; background: linear-gradient(135deg, #efebe9 0%, #d7ccc8 100%); text-align: center; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
<h4 style="color: #3e2723; margin: 0 0 10px 0;">👥 USABILIDAD</h4>
<div style="display: grid; gap: 6px;">
<div style="background: white; padding: 8px; border-radius: 6px; font-size: 11px; border-left: 3px solid #795548;">
<strong>Aprendizaje:</strong> ≤ 2 horas
</div>
<div style="background: white; padding: 8px; border-radius: 6px; font-size: 11px; border-left: 3px solid #795548;">
<strong>Navegadores:</strong> Chrome/Edge/FF
</div>
<div style="background: white; padding: 8px; border-radius: 6px; font-size: 11px; border-left: 3px solid #795548;">
<strong>Resolución:</strong> ≥ 1024x768
</div>
<div style="background: white; padding: 8px; border-radius: 6px; font-size: 11px; border-left: 3px solid #795548;">
<strong>Móvil:</strong> Responsive
</div>
</div>
</div>

</div>

---

## 6. PROCESOS DE DESARROLLO ÁGIL ADAPTADOS 📋

### 6.1 Marco Scrum Biodegradable

<div style="display: grid; grid-template-columns: repeat(3, 1fr); gap: 20px; margin: 25px 0;">

<div style="border: 4px solid #2196f3; border-radius: 15px; padding: 20px; background: linear-gradient(135deg, #e3f2fd 0%, #90caf9 100%); box-shadow: 0 6px 12px rgba(0,0,0,0.15);">
<h4 style="color: #0d47a1; margin: 0 0 15px 0; text-align: center;">👥 ROLES ESPECIALIZADOS</h4>
<div style="display: grid; gap: 12px;">
<div style="background: white; padding: 12px; border-radius: 8px; border-left: 4px solid #2196f3;">
<strong style="color: #1976d2;">Product Owner Industrial:</strong><br>
<span style="font-size: 13px;">Define funcionalidades de monitoreo y control</span>
</div>
<div style="background: white; padding: 12px; border-radius: 8px; border-left: 4px solid #2196f3;">
<strong style="color: #1976d2;">Scrum Master Laravel:</strong><br>
<span style="font-size: 13px;">Facilitador especializado en stack tecnológico</span>
</div>
<div style="background: white; padding: 12px; border-radius: 8px; border-left: 4px solid #2196f3;">
<strong style="color: #1976d2;">Dev Team Full-Stack:</strong><br>
<span style="font-size: 13px;">Backend Laravel + Frontend Vue.js</span>
</div>
<div style="background: white; padding: 12px; border-radius: 8px; border-left: 4px solid #2196f3;">
<strong style="color: #1976d2;">QA Industrial:</strong><br>
<span style="font-size: 13px;">Testing especializado en procesos industriales</span>
</div>
</div>
</div>

<div style="border: 4px solid #4caf50; border-radius: 15px; padding: 20px; background: linear-gradient(135deg, #e8f5e8 0%, #a5d6a7 100%); box-shadow: 0 6px 12px rgba(0,0,0,0.15);">
<h4 style="color: #2e7d32; margin: 0 0 15px 0; text-align: center;">⚡ SPRINTS INDUSTRIALES</h4>
<div style="display: grid; gap: 12px;">
<div style="background: white; padding: 12px; border-radius: 8px; border-left: 4px solid #4caf50;">
<strong style="color: #388e3c;">Duración:</strong><br>
<span style="font-size: 13px;">Sprints cortos iterativos</span>
</div>
<div style="background: white; padding: 12px; border-radius: 8px; border-left: 4px solid #4caf50;">
<strong style="color: #388e3c;">Planning:</strong><br>
<span style="font-size: 13px;">Sesión extendida con stakeholders industriales</span>
</div>
<div style="background: white; padding: 12px; border-radius: 8px; border-left: 4px solid #4caf50;">
<strong style="color: #388e3c;">Daily Scrum:</strong><br>
<span style="font-size: 13px;">Reunión breve enfocada en monitoreo RT</span>
</div>
<div style="background: white; padding: 12px; border-radius: 8px; border-left: 4px solid #4caf50;">
<strong style="color: #388e3c;">Review + Retro:</strong><br>
<span style="font-size: 13px;">Sesión completa con demo en ambiente productivo</span>
</div>
</div>
</div>

<div style="border: 4px solid #ff9800; border-radius: 15px; padding: 20px; background: linear-gradient(135deg, #fff8e1 0%, #ffcc80 100%); box-shadow: 0 6px 12px rgba(0,0,0,0.15);">
<h4 style="color: #e65100; margin: 0 0 15px 0; text-align: center;">📊 ARTEFACTOS ADAPTADOS</h4>
<div style="display: grid; gap: 12px;">
<div style="background: white; padding: 12px; border-radius: 8px; border-left: 4px solid #ff9800;">
<strong style="color: #f57c00;">Product Backlog Industrial:</strong><br>
<span style="font-size: 13px;">User Stories con criterios biodegradables</span>
</div>
<div style="background: white; padding: 12px; border-radius: 8px; border-left: 4px solid #ff9800;">
<strong style="color: #f57c00;">Sprint Backlog Laravel:</strong><br>
<span style="font-size: 13px;">Tasks específicas MVC + API + Tests</span>
</div>
<div style="background: white; padding: 12px; border-radius: 8px; border-left: 4px solid #ff9800;">
<strong style="color: #f57c00;">Increment Industrial:</strong><br>
<span style="font-size: 13px;">Funcionalidad deployable en producción</span>
</div>
<div style="background: white; padding: 12px; border-radius: 8px; border-left: 4px solid #ff9800;">
<strong style="color: #f57c00;">DoD Biodegradable:</strong><br>
<span style="font-size: 13px;">Criterios específicos validación industrial</span>
</div>
</div>
</div>

</div>

### 6.2 Ceremonias y Timeboxing

<div style="display: grid; grid-template-columns: repeat(2, 1fr); gap: 20px; margin: 25px 0;">

<div style="border: 4px solid #9c27b0; border-radius: 15px; padding: 20px; background: linear-gradient(135deg, #f3e5f5 0%, #ce93d8 100%); box-shadow: 0 6px 12px rgba(0,0,0,0.15);">
<h4 style="color: #4a148c; margin: 0 0 15px 0; text-align: center;">🎯 SPRINT PLANNING INDUSTRIAL</h4>
<div style="display: grid; gap: 10px;">
<div style="background: white; padding: 10px; border-radius: 6px; border-left: 3px solid #9c27b0;">
<strong>Parte 1:</strong> Qué vamos a desarrollar<br>
<span style="font-size: 12px;">• Refinamiento Product Backlog Industrial<br>• Estimación con Planning Poker<br>• Velocity team histórica</span>
</div>
<div style="background: white; padding: 10px; border-radius: 6px; border-left: 3px solid #9c27b0;">
<strong>Parte 2:</strong> Cómo lo vamos a desarrollar<br>
<span style="font-size: 12px;">• Diseño técnico Laravel + Vue<br>• Task breakdown structure<br>• Definition of Done específica</span>
</div>
</div>
</div>

<div style="border: 4px solid #607d8b; border-radius: 15px; padding: 20px; background: linear-gradient(135deg, #eceff1 0%, #b0bec5 100%); box-shadow: 0 6px 12px rgba(0,0,0,0.15);">
<h4 style="color: #263238; margin: 0 0 15px 0; text-align: center;">🔄 DAILY SCRUM BIODEGRADABLE</h4>
<div style="display: grid; gap: 10px;">
<div style="background: white; padding: 10px; border-radius: 6px; border-left: 3px solid #607d8b;">
<strong>Timeboxing:</strong> Reunión breve<br>
<span style="font-size: 12px;">• ¿Qué hice ayer para el Sprint Goal?<br>• ¿Qué voy a hacer hoy?<br>• ¿Hay impedimentos técnicos/industriales?</span>
</div>
<div style="background: white; padding: 10px; border-radius: 6px; border-left: 3px solid #607d8b;">
<strong>Foco Especial:</strong> Monitoreo en tiempo real<br>
<span style="font-size: 12px;">• Status APIs críticas<br>• Performance dashboard<br>• Alertas sistema industrial</span>
</div>
</div>
</div>

<div style="border: 4px solid #3f51b5; border-radius: 15px; padding: 20px; background: linear-gradient(135deg, #e8eaf6 0%, #9fa8da 100%); box-shadow: 0 6px 12px rgba(0,0,0,0.15);">
<h4 style="color: #1a237e; margin: 0 0 15px 0; text-align: center;">🚀 SPRINT REVIEW PRODUCTIVO</h4>
<div style="display: grid; gap: 10px;">
<div style="background: white; padding: 10px; border-radius: 6px; border-left: 3px solid #3f51b5;">
<strong>Demo Live:</strong><br>
<span style="font-size: 12px;">• Funcionalidades en ambiente productivo<br>• Casos de uso reales biodegradables<br>• Métricas de rendimiento alcanzadas</span>
</div>
<div style="background: white; padding: 10px; border-radius: 6px; border-left: 3px solid #3f51b5;">
<strong>Feedback Stakeholders:</strong><br>
<span style="font-size: 12px;">• Validación criterios industriales<br>• Adaptaciones Product Backlog<br>• Próximas prioridades</span>
</div>
</div>
</div>

<div style="border: 4px solid #f44336; border-radius: 15px; padding: 20px; background: linear-gradient(135deg, #ffebee 0%, #ef9a9a 100%); box-shadow: 0 6px 12px rgba(0,0,0,0.15);">
<h4 style="color: #b71c1c; margin: 0 0 15px 0; text-align: center;">📈 SPRINT RETROSPECTIVE MEJORA</h4>
<div style="display: grid; gap: 10px;">
<div style="background: white; padding: 10px; border-radius: 6px; border-left: 3px solid #f44336;">
<strong>Inspección:</strong><br>
<span style="font-size: 12px;">• ¿Qué funcionó bien?<br>• ¿Qué se puede mejorar?<br>• ¿Qué comprometemos cambiar?</span>
</div>
<div style="background: white; padding: 10px; border-radius: 6px; border-left: 3px solid #f44336;">
<strong>Adaptación:</strong><br>
<span style="font-size: 12px;">• Plan de mejora próximo Sprint<br>• Ajustes process industriales<br>• Optimizaciones técnicas Laravel/Vue</span>
</div>
</div>
</div>

</div>

---

## 7. ESTRATEGIAS DE TESTING IEEE 829 ADAPTADAS 🧪

### 7.1 Niveles de Testing Industriales

<div style="display: grid; grid-template-columns: repeat(4, 1fr); gap: 18px; margin: 25px 0;">

<div style="border: 4px solid #4caf50; border-radius: 12px; padding: 18px; background: linear-gradient(135deg, #e8f5e8 0%, #a5d6a7 100%); text-align: center; box-shadow: 0 5px 10px rgba(0,0,0,0.12);">
<h4 style="color: #2e7d32; margin: 0 0 12px 0;">🔬 UNIT TESTING</h4>
<div style="display: grid; gap: 8px;">
<div style="background: white; padding: 10px; border-radius: 6px; font-size: 12px; border-left: 3px solid #4caf50;">
<strong>PHPUnit:</strong> Laravel Models/Services
</div>
<div style="background: white; padding: 10px; border-radius: 6px; font-size: 12px; border-left: 3px solid #4caf50;">
<strong>Jest:</strong> Vue.js Components
</div>
<div style="background: white; padding: 10px; border-radius: 6px; font-size: 12px; border-left: 3px solid #4caf50;">
<strong>Cobertura:</strong> Alta líneas código
</div>
<div style="background: white; padding: 10px; border-radius: 6px; font-size: 12px; border-left: 3px solid #4caf50;">
<strong>Automatización:</strong> CI/CD Pipeline
</div>
</div>
</div>

<div style="border: 4px solid #2196f3; border-radius: 12px; padding: 18px; background: linear-gradient(135deg, #e3f2fd 0%, #90caf9 100%); text-align: center; box-shadow: 0 5px 10px rgba(0,0,0,0.12);">
<h4 style="color: #0d47a1; margin: 0 0 12px 0;">⚙️ INTEGRATION</h4>
<div style="display: grid; gap: 8px;">
<div style="background: white; padding: 10px; border-radius: 6px; font-size: 12px; border-left: 3px solid #2196f3;">
<strong>API Testing:</strong> Postman/Insomnia
</div>
<div style="background: white; padding: 10px; border-radius: 6px; font-size: 12px; border-left: 3px solid #2196f3;">
<strong>Database:</strong> SQLite en memoria
</div>
<div style="background: white; padding: 10px; border-radius: 6px; font-size: 12px; border-left: 3px solid #2196f3;">
<strong>Laravel Feature:</strong> HTTP Tests
</div>
<div style="background: white; padding: 10px; border-radius: 6px; font-size: 12px; border-left: 3px solid #2196f3;">
<strong>Real-time:</strong> WebSocket testing
</div>
</div>
</div>

<div style="border: 4px solid #ff9800; border-radius: 12px; padding: 18px; background: linear-gradient(135deg, #fff8e1 0%, #ffcc80 100%); text-align: center; box-shadow: 0 5px 10px rgba(0,0,0,0.12);">
<h4 style="color: #e65100; margin: 0 0 12px 0;">🖥️ E2E TESTING</h4>
<div style="display: grid; gap: 8px;">
<div style="background: white; padding: 10px; border-radius: 6px; font-size: 12px; border-left: 3px solid #ff9800;">
<strong>Cypress:</strong> User Journeys completos
</div>
<div style="background: white; padding: 10px; border-radius: 6px; font-size: 12px; border-left: 3px solid #ff9800;">
<strong>Playwright:</strong> Cross-browser testing
</div>
<div style="background: white; padding: 10px; border-radius: 6px; font-size: 12px; border-left: 3px solid #ff9800;">
<strong>Escenarios:</strong> Procesos industriales
</div>
<div style="background: white; padding: 10px; border-radius: 6px; font-size: 12px; border-left: 3px solid #ff9800;">
<strong>Ambiente:</strong> Staging production-like
</div>
</div>
</div>

<div style="border: 4px solid #9c27b0; border-radius: 12px; padding: 18px; background: linear-gradient(135deg, #f3e5f5 0%, #ce93d8 100%); text-align: center; box-shadow: 0 5px 10px rgba(0,0,0,0.12);">
<h4 style="color: #4a148c; margin: 0 0 12px 0;">🏭 INDUSTRIAL</h4>
<div style="display: grid; gap: 8px;">
<div style="background: white; padding: 10px; border-radius: 6px; font-size: 12px; border-left: 3px solid #9c27b0;">
<strong>Performance:</strong> Apache JMeter
</div>
<div style="background: white; padding: 10px; border-radius: 6px; font-size: 12px; border-left: 3px solid #9c27b0;">
<strong>Load Testing:</strong> Múltiples usuarios concurrentes
</div>
<div style="background: white; padding: 10px; border-radius: 6px; font-size: 12px; border-left: 3px solid #9c27b0;">
<strong>Stress:</strong> Picos de producción
</div>
<div style="background: white; padding: 10px; border-radius: 6px; font-size: 12px; border-left: 3px solid #9c27b0;">
<strong>Security:</strong> OWASP ZAP scans
</div>
</div>
</div>

</div>
</div>
<div style="background: white; padding: 8px; border-radius: 6px; font-size: 11px; border-left: 3px solid #4caf50;">
<strong>RTO:</strong> Rápida
</div>
<div style="background: white; padding: 8px; border-radius: 6px; font-size: 11px; border-left: 3px solid #4caf50;">
<strong>RPO:</strong> Protegidos
</div>
<div style="background: white; padding: 8px; border-radius: 6px; font-size: 11px; border-left: 3px solid #4caf50;">
<strong>Backup:</strong> Automático frecuente
</div>
</div>
</div>

<div style="border: 4px solid #795548; border-radius: 12px; padding: 15px; background: linear-gradient(135deg, #efebe9 0%, #d7ccc8 100%); text-align: center; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
<h4 style="color: #3e2723; margin: 0 0 10px 0;">👥 USABILIDAD</h4>
<div style="display: grid; gap: 6px;">
<div style="background: white; padding: 8px; border-radius: 6px; font-size: 11px; border-left: 3px solid #795548;">
<strong>Aprendizaje:</strong> Intuitivo
</div>
<div style="background: white; padding: 8px; border-radius: 6px; font-size: 11px; border-left: 3px solid #795548;">
<strong>Navegadores:</strong> Modernos
</div>
<div style="background: white; padding: 8px; border-radius: 6px; font-size: 11px; border-left: 3px solid #795548;">
<strong>Resolución:</strong> Estándar
</div>
<div style="background: white; padding: 8px; border-radius: 6px; font-size: 11px; border-left: 3px solid #795548;">
<strong>Móvil:</strong> Adaptativo
</div>
</div>
</div>

</div>
</div>
