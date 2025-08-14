# Roadmap Python, Terraform, Kubernetes, Helm – 12 Semanas

## Fase 1: Fundamentos de DevOps y Python
**Objetivo de la fase:** Comprender los conceptos básicos de DevOps y dominar Python para automatización inicial.

### Semana 1 (Semana 1 de la Fase 1)
**Tema:** Introducción a DevOps y Python  
**Objetivo:** Entender principios de DevOps y configurar entorno Python.  
**Contenidos:**
- Principios de DevOps
- Ciclo de vida de software
- Introducción a Python
- Instalación de Python y VSCode
- Control de versiones con Git
**Práctica:**
- Configurar entorno Python y Git
- Crear scripts básicos
- Uso de repositorios remotos
**Proyectos:**
1) Script que imprime estado del sistema
**Revisión:** Revisión de scripts y configuración de entorno  
**Tags:** devops, python, fundamentos

### Semana 2 (Semana 2 de la Fase 1)
**Tema:** Python para automatización  
**Objetivo:** Escribir scripts Python para tareas repetitivas.  
**Contenidos:**
- Sintaxis Python
- Manejo de archivos
- Librerías estándar
- Virtualenv
**Práctica:**
- Crear script que lee y escribe archivos
- Uso de argparse
**Proyectos:**
1) Script para limpiar logs antiguos
**Revisión:** Revisión de código y buenas prácticas  
**Tags:** python, automatización

## Fase 2: Fundamentos de Infraestructura como Código
**Objetivo de la fase:** Comprender Terraform y los principios de IaC.

### Semana 3 (Semana 1 de la Fase 2)
**Tema:** Introducción a Terraform  
**Objetivo:** Entender IaC y configurar entorno Terraform.  
**Contenidos:**
- Conceptos IaC
- Instalación de Terraform
- Providers y recursos básicos
**Práctica:**
- Crear configuración para VM simple
- Aplicar y destruir infraestructura
**Proyectos:**
1) Infraestructura mínima en nube local
**Revisión:** Validar despliegue y destrucción controlada  
**Tags:** terraform, iac

### Semana 4 (Semana 2 de la Fase 2)
**Tema:** Variables y módulos en Terraform  
**Objetivo:** Modularizar infraestructura para reuso.  
**Contenidos:**
- Variables y outputs
- Módulos locales y remotos
- Buenas prácticas
**Práctica:**
- Refactorizar infra usando módulos
- Añadir variables de configuración
**Proyectos:**
1) Infra modular con red y servidor
**Revisión:** Revisión de estructura modular  
**Tags:** terraform, módulos

## Fase 3: Contenedores con Docker y Kubernetes
**Objetivo de la fase:** Aprender a desplegar y gestionar aplicaciones en contenedores y Kubernetes.

### Semana 5 (Semana 1 de la Fase 3)
**Tema:** Introducción a Docker y Kubernetes  
**Objetivo:** Crear imágenes Docker y entender Kubernetes básico.  
**Contenidos:**
- Dockerfile
- docker build / run
- Pods y Deployments en Kubernetes
**Práctica:**
- Crear imagen Docker para app Python
- Desplegar pod en minikube
**Proyectos:**
1) App Python en Docker y pod
**Revisión:** Validar imagen y pod funcionando  
**Tags:** docker, kubernetes

### Semana 6 (Semana 2 de la Fase 3)
**Tema:** Servicios y volúmenes  
**Objetivo:** Exponer apps y gestionar datos persistentes.  
**Contenidos:**
- Services y tipos
- Persistent Volumes
- ConfigMaps y Secrets
**Práctica:**
- Exponer app con LoadBalancer
- Añadir PV y PVC
**Proyectos:**
1) App con base de datos y volumen persistente
**Revisión:** Revisión de conectividad y persistencia  
**Tags:** kubernetes, servicios

## Fase 4: Gestión de despliegues con Helm
**Objetivo de la fase:** Implementar y gestionar paquetes Kubernetes con Helm.

### Semana 7 (Semana 1 de la Fase 4)
**Tema:** Introducción a Helm  
**Objetivo:** Instalar y usar Helm para despliegues simples.  
**Contenidos:**
- Instalación de Helm
- Charts básicos
- helm install / upgrade
**Práctica:**
- Crear chart básico para app Python
**Proyectos:**
1) Chart Helm para app existente
**Revisión:** Validar despliegue con Helm  
**Tags:** helm, kubernetes

### Semana 8 (Semana 2 de la Fase 4)
**Tema:** Helm avanzado y repositorios  
**Objetivo:** Gestionar repositorios y valores dinámicos.  
**Contenidos:**
- helm repo
- values.yaml avanzados
- Plantillas y helpers
**Práctica:**
- Personalizar despliegue con values
- Uso de condicionales en templates
**Proyectos:**
1) Chart con parámetros configurables
**Revisión:** Revisión de parametrización  
**Tags:** helm, templates

## Fase 5: CI/CD con GitHub Actions
**Objetivo de la fase:** Automatizar pruebas y despliegues con pipelines CI/CD.

### Semana 9 (Semana 1 de la Fase 5)
**Tema:** Introducción a CI/CD  
**Objetivo:** Configurar pipeline básico en GitHub Actions.  
**Contenidos:**
- YAML workflows
- Jobs y steps
- Acciones predefinidas
**Práctica:**
- Pipeline para ejecutar tests Python
**Proyectos:**
1) CI básico para validar código
**Revisión:** Revisión de ejecución en Actions  
**Tags:** cicd, github-actions

### Semana 10 (Semana 2 de la Fase 5)
**Tema:** Despliegue automatizado  
**Objetivo:** Integrar Terraform y Kubernetes en CI/CD.  
**Contenidos:**
- Secrets en GitHub
- Terraform apply
- kubectl en pipelines
**Práctica:**
- Pipeline que despliega infra y app
**Proyectos:**
1) CD para app Python
**Revisión:** Validar despliegue automatizado  
**Tags:** cicd, despliegue

## Fase 6: Proyecto Integrador DevOps
**Objetivo de la fase:** Desarrollar y desplegar una solución completa con herramientas aprendidas.

### Semana 11 (Semana 1 de la Fase 6)
**Tema:** Diseño de proyecto  
**Objetivo:** Planificar arquitectura y stack del proyecto integrador.  
**Contenidos:**
- Definición de requisitos
- Diagramas de arquitectura
- Selección de tecnologías
**Práctica:**
- Crear plan y backlog del proyecto
**Proyectos:**
1) Documento de diseño y backlog
**Revisión:** Revisión de plan y alcance  
**Tags:** proyecto, arquitectura

### Semana 12 (Semana 2 de la Fase 6)
**Tema:** Implementación y entrega  
**Objetivo:** Implementar, probar y entregar el proyecto integrador.  
**Contenidos:**
- Desarrollo de funcionalidades
- Infraestructura como código
- CI/CD y monitoreo
**Práctica:**
- Desplegar proyecto en entorno real
**Proyectos:**
1) Proyecto final desplegado
**Revisión:** Demo final y retroalimentación  
**Tags:** proyecto, entrega-final
