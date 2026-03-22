# [NOMBRE DEL SISTEMA] — Documento de Arquitectura

> **Versión:** 1.0  
> **Fecha:** YYYY-MM-DD  
> **Autor:** [nombre]  
> **Estado:** Draft | Review | Aprobado  

---

## 1. Descripción del Sistema

<!-- Qué hace este sistema, cuál es su propósito de negocio y técnico -->

**Propósito:**  
**Tecnologías principales:**  
**Entorno(s):** dev | pre | pro  

---

## 2. Diagrama y Dependencias

<!-- Diagrama de arquitectura en texto o referencia a imagen -->
```
[Diagrama ASCII o referencia a fichero de imagen]
```

### Dependencias entrantes (quién me llama)
| Sistema | Protocolo | Descripción |
|---------|-----------|-------------|
|         |           |             |

### Dependencias salientes (a quién llamo)
| Sistema | Protocolo | Descripción |
|---------|-----------|-------------|
|         |           |             |

---

## 3. Despliegue

**Plataforma:** AKS | ECS | EC2 | Lambda | otro  
**Método de despliegue:** Helm | Terraform | Jenkins Pipeline | otro  
**Repositorio:** [URL]  
**Rama principal:** main | master  

### Variables de entorno requeridas
| Variable | Descripción | Obligatoria |
|----------|-------------|-------------|
|          |             | Sí / No     |

### Proceso de despliegue
```
1. 
2. 
3. 
```

---

## 4. Gestión de Secretos

**Gestor de secretos:** Azure Key Vault | AWS Secrets Manager | Vault | otro  
**Método de inyección:** CSI Driver | ENV | otro  

| Secreto | Descripción | Rotación |
|---------|-------------|----------|
|         |             |          |

---

## 5. Monitorización y Alertas

**Herramienta:** Prometheus | Datadog | Azure Monitor | otro  
**Dashboard:** [URL o nombre]  

### Métricas clave
| Métrica | Umbral Warning | Umbral Critical |
|---------|----------------|-----------------|
|         |                |                 |

### Logs
**Ubicación:** [ruta o sistema centralizado]  
**Retención:**  

---

## 6. Modos de Fallo Conocidos

| Fallo | Síntomas | Causa probable |
|-------|----------|----------------|
|       |          |                |

---

## 7. Recuperación

### Procedimiento general
```
1. 
2. 
3. 
```

### Rollback de despliegue
```bash
# Comando de rollback
```

**RTO estimado:**  
**RPO estimado:**  

---

## 8. Contactos y Responsabilidades

| Rol | Nombre | Contacto |
|-----|--------|----------|
| Responsable técnico | | |
| Equipo propietario | | |
| Escalado L2 | | |

---

## Historial de cambios

| Fecha | Versión | Autor | Cambio |
|-------|---------|-------|--------|
|       | 1.0     |       | Versión inicial |
