# DALINA · AlimentIA Consulting Group

Asistente de alta nutricional para servicios sociosanitarios.

## Stack
- HTML/CSS/JS — single file, sin frameworks
- Supabase — base de datos compartida con Rutty y app del comensal
- Claude API — análisis de informes médicos con IA
- Netlify — despliegue automático desde GitHub

## Despliegue
1. Fork o clone este repo
2. Conecta a Netlify → Build: `public/`
3. La app se despliega automáticamente en cada push a `main`

## Variables de entorno
No necesita variables de entorno — las credenciales de Supabase son públicas (anon key con RLS).
La API key de Claude va en el código del formulario (flujo de visitadora, no expuesto al público).

## AlimentIA Consulting Group LLC
- Dalina · Alta nutricional
- Rutty · Reparto inteligente  
- App Comensal · Seguimiento familiar
