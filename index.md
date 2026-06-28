---
layout: default
title: FrostCore | Jorge de la Flor — Software Architect & Systems Developer
---

<div class="profile-hero">
  <img src="{{ '/assets/images/avatar.jpg' | relative_url }}" alt="Jorge de la Flor" class="profile-avatar" onerror="this.style.display='none'">
  
  <h1 class="profile-name">FrostCore</h1>
  <p class="profile-title" style="font-size: 1.1rem; font-weight: 400;">Jorge A. de la Flor</p>
  <p class="profile-title" style="font-weight: 400; color: var(--text-secondary);">
    Software Architect & Systems Developer
  </p>
  <p class="profile-title" style="font-weight: 300; color: var(--text-muted); font-size: 0.95rem;">
    Cloud-agnostic · Language Engineering · Embedded Architectures
  </p>
  
  <div class="tech-badges">
    <span class="tech-badge rust"><i class="fas fa-cog"></i> Rust</span>
    <span class="tech-badge python"><i class="fab fa-python"></i> Python</span>
    <span class="tech-badge cpp"><i class="fas fa-microchip"></i> C/C++</span>
    <span class="tech-badge embedded"><i class="fas fa-microchip"></i> Embedded</span>
    <span class="tech-badge ml"><i class="fas fa-code-branch"></i> Language Engineering</span>
  </div>
  
  <div class="social-links">
    <a href="https://github.com/{{ site.social.github }}" class="social-link" title="GitHub" target="_blank"><i class="fab fa-github"></i></a>
    <a href="https://linkedin.com/in/{{ site.social.linkedin }}" class="social-link" title="LinkedIn" target="_blank"><i class="fab fa-linkedin-in"></i></a>
    <a href="mailto:{{ site.author.email }}" class="social-link" title="Email"><i class="fas fa-envelope"></i></a>
  </div>
</div>

---

## Sobre mí

<div style="font-size: 1.05rem; line-height: 1.8; color: var(--text-secondary);">
  <p><strong>Arquitecto de software y desarrollador de sistemas</strong> especializado en infraestructura cloud-agnóstica, sistemas embebidos y tooling de lenguajes. Creador de <strong>Apider</strong>, <strong>Pyperanto</strong> y <strong>OMNI-PY</strong> — tres plataformas que resuelven problemas de portabilidad, automatización y generación de código.</p>
  
  <p>Los principios arquitectónicos que unifican estos proyectos están formalizados como el <strong>Modelo Agnóstico (AMP)</strong> en mi libro en preparación: <em>The Agnostic Engineer: Architecture Beyond Infrastructure</em>.</p>
  
  <p>Combino una formación en <strong>International Business</strong> con experiencia práctica en ingeniería de software. He sido ponente invitado en <strong>Microsoft Build 2026</strong> y en <strong>Azure User Group Latam</strong>.</p>
</div>

<p style="margin-top: 1.5rem;">
  <a href="{{ '/md_pages/about/' | relative_url }}" class="cta-link">
    Conoce mi trayectoria completa →
  </a>
</p>

---

## Proyectos destacados {#proyectos}

<div class="card-grid">
  <div class="card">
    <h3 class="card-title"><i class="fas fa-cloud" style="color: #4fc3f7;"></i> Apider SDK</h3>
    <p class="card-desc">
      Runtime multi-tenant serverless en Azure Functions. Publicado en PyPI (<code>pip install apider</code>). 
      Aislamiento por ContextVar, cifrado Fernet, servidor MCP stateless y facturación con Paddle. 
      <strong>61 tests</strong> en CI.
    </p>
    <a href="https://pypi.org/project/apider" class="card-link" target="_blank">Ver en PyPI →</a>
  </div>
  
  <div class="card">
    <h3 class="card-title"><i class="fas fa-microchip" style="color: #DEA584;"></i> Pyperanto</h3>
    <p class="card-desc">
      Tooling propietario para generación de código firmware embebido. 
      Soporte para <strong>4+ familias de MCUs</strong> con emisión automática de código 
      a partir de modelos de configuración hardware-independientes.
    </p>
    <span style="font-size: 0.8rem; color: var(--text-muted);">🔒 IP filing en progreso</span>
  </div>
  
  <div class="card">
    <h3 class="card-title"><i class="fas fa-code" style="color: #8b5cf6;"></i> OMNI-PY</h3>
    <p class="card-desc">
      Transpilador de Python a múltiples lenguajes (Java, Go, JavaScript). 
      Capa AST en Python + <strong>TypeTracker en Rust</strong> (PyO3 FFI) que realiza 
      inferencia de tipos y análisis de nulabilidad.
    </p>
  </div>
</div>

---

## Filosofía arquitectónica

<div style="background: var(--bg-card); border-left: 4px solid var(--accent-rust); padding: 1.5rem; border-radius: var(--radius); margin: 1.5rem 0;">
  <p style="font-weight: 500; font-size: 1.1rem; margin-bottom: 0.5rem;">
    <i class="fas fa-book" style="color: var(--accent-rust); margin-right: 0.5rem;"></i>
    <strong>The Agnostic Engineer: Architecture Beyond Infrastructure</strong>
  </p>
  <p style="color: var(--text-secondary); margin-bottom: 0;">
    Formaliza el principio de <strong>"Agnosticismo por Transformación"</strong> como principio arquitectónico unificado, aplicado en tres dominios: <strong>cloud</strong> (Apider), <strong>embedded</strong> (Pyperanto) y <strong>language tooling</strong> (OMNI-PY).
  </p>
</div>

---

## Stack Tecnológico {#stack}

<div style="text-align: center; margin-bottom: 1rem;">
  <p style="font-weight: 500; font-size: 1.1rem; color: var(--text-secondary);">
    <strong>Lenguajes principales:</strong> Python · Rust · C/C++
  </p>
  <p style="font-weight: 400; font-size: 0.95rem; color: var(--text-muted);">
    <span style="display: inline-block; margin: 0.3rem 0.5rem; padding: 0.2rem 0.8rem; border-radius: 20px; background: var(--bg-secondary); border: 1px solid var(--border-color);">Azure Functions</span>
    <span style="display: inline-block; margin: 0.3rem 0.5rem; padding: 0.2rem 0.8rem; border-radius: 20px; background: var(--bg-secondary); border: 1px solid var(--border-color);">AST</span>
    <span style="display: inline-block; margin: 0.3rem 0.5rem; padding: 0.2rem 0.8rem; border-radius: 20px; background: var(--bg-secondary); border: 1px solid var(--border-color);">PyO3</span>
    <span style="display: inline-block; margin: 0.3rem 0.5rem; padding: 0.2rem 0.8rem; border-radius: 20px; background: var(--bg-secondary); border: 1px solid var(--border-color);">ESP32/STM32</span>
    <span style="display: inline-block; margin: 0.3rem 0.5rem; padding: 0.2rem 0.8rem; border-radius: 20px; background: var(--bg-secondary); border: 1px solid var(--border-color);">MQTT</span>
    <span style="display: inline-block; margin: 0.3rem 0.5rem; padding: 0.2rem 0.8rem; border-radius: 20px; background: var(--bg-secondary); border: 1px solid var(--border-color);">Docker</span>
    <span style="display: inline-block; margin: 0.3rem 0.5rem; padding: 0.2rem 0.8rem; border-radius: 20px; background: var(--bg-secondary); border: 1px solid var(--border-color);">CI/CD</span>
  </p>
</div>

---

## ¿Colaboramos?

Busco oportunidades de <strong>investigación</strong> en arquitectura agnóstica, ingeniería de lenguajes y sistemas distribuidos, así como proyectos de <strong>consultoría</strong> y <strong>desarrollo</strong>.

📩 <strong>Escríbeme a <a href="mailto:{{ site.author.email }}" style="color: var(--accent-rust);">{{ site.author.email }}</a></strong>

<p style="margin-top: 1.5rem; text-align: center;">
  <a href="mailto:{{ site.author.email }}" class="cta-button">
    <i class="fas fa-paper-plane" style="margin-right: 0.5rem;"></i> Contactar ahora
  </a>
</p>
