# Mentoria: Ciencia de datos aplicada a la predicción de licencias médicas y comportamiento de los colaboradores.

## Repositorio para gestionar la mentoria de la Diplomatura en Ciencia de Datos - FAMAF

Trabajaremos con datos obtenidos de una plataforma de salud ocupacional con el objetivo de predecir la carga de licencias médicas. Se propone realizar un análisis temporal a diferentes escalas, e identificar las variables asociadas que expliquen el número de licencias y/o diagnósticos involucrados. 

## Breve descripcion del dataset

El dataset consiste en datos de licencias médicas solicitadas por colaboradores a través de una aplicación, para los años 2021 y 2022, con su diagnóstico asociado. Además contaremos con algunos atributos identificatorios de los usuarios. 

## Diccionario de datos

- numero_licencia: Número identificatorio de la licencia
- fecha_creacion: Fecha en la que se solicita la licencia 
- dispositivo_acceso: Dispositivo a traves del cual el colaborador solicita la licencia: WEB para la aplicación, y APP para la aplicación movil
- dias_solicitados: Días solicitados por el colaborador
- fecha_inicio: Fecha a partir de la cual comienza la licencia
- fecha_fin: Fecha de finalización de la licencia
- diagnostico: Diagnóstico médico asociado a la licencia
- id_diagnostico: Número identificatorio del diagnóstico
- id_usuario: Número identificatorio del colaborador que solicitó la licencia
- fecha_nacimiento: Fecha de nacimiento del colaborador que solicitó la licencia
- genero: Género con el que se identifica el colaborador que solicita la licencia FEMALE, MALE, OTHER
- tipo_licencia: Tipo de licencia solicitada por el colaborador Médica o Médica por Hospitalización
- estado_civil: Estado Civil del colaborador que solicita la licencia 
- dias_aprobados: Días que aprueba el auditor que controla la licencia
- decision_medica: Decisión final asociada a la licencian EDITAR_Y_APROBAR, APROBAR o RECHAZAR
- id_auditor: Número identificatorio del auditor que controla la licencia
- motivo_rechazo: Motivo por el cuál se rechaza una licencia
- categoria_diagnostico: Grupo al que pertenece el diagnostico asociado a la licencia
