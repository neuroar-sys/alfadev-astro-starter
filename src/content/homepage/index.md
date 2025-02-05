---
# Configuración de la página de inicio

banner:
  title: 'Transforma <span class="text-accent text-shadow-[0px_5px_15px] shadow-accent/10">Tus Hábitos  </span> En tan solo <span class="text-secondary"> 21 días </span>'
  title_size: "text-4xl md:text-6xl"
  content: "Unite a un programa intensivo y grupal para cambiar tu vida con desafíos diarios y seguimiento personalizado."  
  image: /images/logo_v5_xl_pfp.webp # Logo actual

sections:
  # ... (resto de secciones)

features:
  # ... (resto de características)

testimonial:
  # ... (resto de testimonios)

call_to_action:
  # ... (resto del call_to_action)

---

import Button from './components/Button.astro'; // Importación corregida

<Button 
  label="¡Únete ahora!" 
  href="https://wa.me/54115757577039?text=estoy%20interesada/o%20en%20el%20programa%20de%20transformación" 
  target="_blank"
  addClasses="bg-blue-500 hover:bg-blue-700" 
/>
