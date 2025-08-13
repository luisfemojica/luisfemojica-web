# luisfemojica.com

Sitio web personal de Luis Fe Mojica - Desarrollador Full Stack

## 🚀 Tecnologías

- **Frontend:** HTML5, CSS3, JavaScript
- **Hosting:** AWS S3 + CloudFront
- **DNS:** Route 53
- **CI/CD:** GitHub Actions
- **Dominio:** luisfemojica.com

## 🌐 URLs

- **Producción:** https://luisfemojica.com
- **S3 Static Website:** http://luisfemojica.com.s3-website-us-east-1.amazonaws.com

## 📁 Estructura

```
├── index.html      # Página principal
├── 404.html        # Página de error
├── robots.txt      # SEO robots
├── sitemap.xml     # Mapa del sitio
└── README.md       # Este archivo
```

## 🛠️ Desarrollo

```bash
# Clonar repositorio
git clone https://github.com/luisfemojica/luisfemojica-web.git
cd luisfemojica-web

# Hacer cambios y commit
git add .
git commit -m "Descripción de cambios"
git push origin main

# Sincronizar con S3 (requiere AWS CLI configurado)
aws s3 sync . s3://luisfemojica.com --delete --exclude ".git/*"
```

## 📧 Contacto

- **Email:** contacto@luisfemojica.com
- **GitHub:** [@luisfemojica](https://github.com/luisfemojica)
- **Ubicación:** Jiutepec, Morelos, México

---

**Estado:** 🚀 En producción  
**Última actualización:** Agosto 2025
