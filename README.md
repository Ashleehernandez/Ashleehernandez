<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CV - Ashlee Hernández</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
            background: #f5f5f5;
        }

        .container {
            max-width: 210mm;
            margin: 20px auto;
            background: white;
            box-shadow: 0 0 20px rgba(0,0,0,0.1);
            display: grid;
            grid-template-columns: 300px 1fr;
            min-height: 297mm;
        }

        .sidebar {
            background: linear-gradient(135deg, #2c3e50 0%, #34495e 100%);
            color: white;
            padding: 30px 25px;
        }

        .main-content {
            padding: 30px 35px;
            background: white;
        }

        .profile-section {
            text-align: center;
            margin-bottom: 30px;
        }

        .profile-img {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            background: #3498db;
            margin: 0 auto 20px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 48px;
            font-weight: bold;
            color: white;
        }

        .name {
            font-size: 24px;
            font-weight: bold;
            margin-bottom: 10px;
            letter-spacing: 1px;
        }

        .title {
            font-size: 14px;
            color: #bdc3c7;
            margin-bottom: 20px;
            line-height: 1.4;
        }

        .contact-info {
            margin-bottom: 30px;
        }

        .contact-item {
            display: flex;
            align-items: center;
            margin-bottom: 12px;
            font-size: 13px;
        }

        .contact-icon {
            width: 16px;
            margin-right: 12px;
            text-align: center;
        }

        .section-title {
            font-size: 16px;
            font-weight: bold;
            margin-bottom: 15px;
            padding-bottom: 8px;
            border-bottom: 2px solid #3498db;
            text-transform: uppercase;
            letter-spacing: 1px;
        }

        .skill-item {
            margin-bottom: 15px;
        }

        .skill-name {
            font-size: 13px;
            margin-bottom: 5px;
            font-weight: 500;
        }

        .skill-bar {
            height: 4px;
            background: rgba(255,255,255,0.2);
            border-radius: 2px;
            overflow: hidden;
        }

        .skill-progress {
            height: 100%;
            background: #3498db;
            border-radius: 2px;
        }

        .skill-list {
            list-style: none;
        }

        .skill-list li {
            padding: 4px 0;
            font-size: 13px;
            position: relative;
            padding-left: 15px;
        }

        .skill-list li:before {
            content: "▸";
            position: absolute;
            left: 0;
            color: #3498db;
        }

        .main-section {
            margin-bottom: 35px;
        }

        .main-section-title {
            font-size: 22px;
            font-weight: bold;
            margin-bottom: 20px;
            color: #2c3e50;
            text-transform: uppercase;
            letter-spacing: 1px;
            border-bottom: 3px solid #3498db;
            padding-bottom: 8px;
        }

        .experience-item, .education-item {
            margin-bottom: 25px;
            position: relative;
            padding-left: 20px;
        }

        .experience-item:before, .education-item:before {
            content: "";
            position: absolute;
            left: 0;
            top: 8px;
            width: 8px;
            height: 8px;
            background: #3498db;
            border-radius: 50%;
        }

        .job-title {
            font-size: 16px;
            font-weight: bold;
            color: #2c3e50;
            margin-bottom: 5px;
        }

        .company {
            font-size: 14px;
            color: #3498db;
            font-weight: 600;
            margin-bottom: 8px;
        }

        .job-description {
            font-size: 13px;
            color: #666;
            line-height: 1.6;
        }

        .job-description ul {
            margin-top: 8px;
            padding-left: 18px;
        }

        .job-description li {
            margin-bottom: 4px;
        }

        .degree {
            font-size: 15px;
            font-weight: bold;
            color: #2c3e50;
        }

        .institution {
            font-size: 13px;
            color: #3498db;
            font-weight: 600;
        }

        .soft-skills {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 15px;
            margin-top: 10px;
        }

        .soft-skill-item {
            background: #f8f9fa;
            padding: 12px;
            border-radius: 5px;
            border-left: 3px solid #3498db;
        }

        .soft-skill-title {
            font-weight: bold;
            color: #2c3e50;
            font-size: 13px;
            margin-bottom: 3px;
        }

        .soft-skill-desc {
            font-size: 12px;
            color: #666;
        }

        @media print {
            .container {
                box-shadow: none;
                margin: 0;
            }
            body {
                background: white;
            }
        }

        @media (max-width: 768px) {
            .container {
                grid-template-columns: 1fr;
                margin: 10px;
            }
            .soft-skills {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="sidebar">
            <div class="profile-section">
                <div class="profile-img">AH</div>
                <h1 class="name">ASHLEE<br>HERNÁNDEZ</h1>
                <p class="title">Técnico en Desarrollo y Administración de Aplicaciones Informáticas</p>
            </div>

            <div class="contact-info">
                <div class="contact-item">
                    <span class="contact-icon">📋</span>
                    <span>402-------5</span>
                </div>
                <div class="contact-item">
                    <span class="contact-icon">📞</span>
                    <span>809-----9712</span>
                </div>
                <div class="contact-item">
                    <span class="contact-icon">✉</span>
                    <span>ashleehernandez0830@gmail.com</span>
                </div>
                <div class="contact-item">
                    <span class="contact-icon">📍</span>
                    <span>Santo Domingo Este, Andrés Boca Chica</span>
                </div>
            </div>

            <div class="section">
                <h3 class="section-title">Lenguajes de Programación</h3>
                <div class="skill-item">
                    <div class="skill-name">C#</div>
                    <div class="skill-bar">
                        <div class="skill-progress" style="width: 90%"></div>
                    </div>
                </div>
                <div class="skill-item">
                    <div class="skill-name">JavaScript</div>
                    <div class="skill-bar">
                        <div class="skill-progress" style="width: 85%"></div>
                    </div>
                </div>
                <div class="skill-item">
                    <div class="skill-name">Java</div>
                    <div class="skill-bar">
                        <div class="skill-progress" style="width: 75%"></div>
                    </div>
                </div>
                <div class="skill-item">
                    <div class="skill-name">Python</div>
                    <div class="skill-bar">
                        <div class="skill-progress" style="width: 70%"></div>
                    </div>
                </div>
                <div class="skill-item">
                    <div class="skill-name">PHP</div>
                    <div class="skill-bar">
                        <div class="skill-progress" style="width: 75%"></div>
                    </div>
                </div>
                <div class="skill-item">
                    <div class="skill-name">SQL</div>
                    <div class="skill-bar">
                        <div class="skill-progress" style="width: 80%"></div>
                    </div>
                </div>
            </div>

            <div class="section">
                <h3 class="section-title">Frameworks & Tecnologías</h3>
                <ul class="skill-list">
                    <li>.NET Framework</li>
                    <li>.NET MAUI</li>
                    <li>ASP.NET Core</li>
                    <li>Entity Framework</li>
                    <li>Laravel</li>
                    <li>React</li>
                    <li>Windows Forms</li>
                </ul>
            </div>

            <div class="section">
                <h3 class="section-title">Testing & QA</h3>
                <ul class="skill-list">
                    <li>Selenium WebDriver</li>
                    <li>Postman (APIs)</li>
                    <li>Pruebas Automatizadas</li>
                    <li>Pruebas Manuales</li>
                    <li>Pruebas de Regresión</li>
                </ul>
            </div>

            <div class="section">
                <h3 class="section-title">ORM & Base de Datos</h3>
                <ul class="skill-list">
                    <li>Entity Framework</li>
                    <li>SQL Server</li>
                    <li>MySQL</li>
                    <li>LINQ</li>
                    <li>PostgreSQL</li>
                </ul>
            </div>

            <div class="section">
                <h3 class="section-title">Herramientas</h3>
                <ul class="skill-list">
                    <li>Git (Control de versiones)</li>
                    <li>Linux & Windows</li>
                    <li>APIs REST</li>
                    <li>HTML5 & CSS3</li>
                    <li>Visual Studio</li>
                </ul>
            </div>
        </div>

        <div class="main-content">
            <div class="main-section">
                <h2 class="main-section-title">Perfil Profesional</h2>
                <p style="text-align: justify; color: #666; font-size: 14px; line-height: 1.6;">
                    Técnico especializado en desarrollo de software con experiencia integral en el ciclo completo de desarrollo: desde el análisis de requerimientos y diseño de soluciones, hasta el desarrollo con C# y .NET, y control de calidad (QA). Sólida experiencia en levantamiento de requerimientos, creación de diagramas de flujo, desarrollo de aplicaciones robustas utilizando Entity Framework, y testing automatizado con Selenium WebDriver. Orientado a resultados con excelentes habilidades analíticas y capacidad de trabajo en equipos multidisciplinarios.
                </p>
            </div>

            <div class="main-section">
                <h2 class="main-section-title">Experiencia Profesional</h2>
                
                <div class="experience-item">
                    <div class="job-title">Analista de Requerimientos</div>
                    <div class="company">ASHPROGRAM (Consultora de Desarrollo de Software)</div>
                    <div class="job-description">
                        <ul>
                            <li><strong>Levantamiento de requerimientos:</strong> Análisis y documentación detallada de necesidades del cliente y especificaciones funcionales del sistema.</li>
                            <li><strong>Análisis de procesos:</strong> Estudio y mapeo de procesos de negocio para identificar oportunidades de mejora y automatización.</li>
                            <li><strong>Diagramas de flujo:</strong> Creación de diagramas de flujo de aplicaciones y procesos para visualizar la lógica del sistema.</li>
                            <li><strong>Documentación técnica:</strong> Elaboración de especificaciones técnicas y funcionales para guiar el desarrollo.</li>
                            <li><strong>Comunicación cliente-desarrollo:</strong> Facilitación de comunicación efectiva entre stakeholders y equipo técnico.</li>
                        </ul>
                    </div>
                </div>

                <div class="experience-item">
                    <div class="job-title">Desarrolladora de Software</div>
                    <div class="company">ASHPROGRAM (Consultora de Desarrollo de Software)</div>
                    <div class="job-description">
                        <ul>
                            <li><strong>Desarrollo en C#:</strong> Creación de aplicaciones robustas utilizando C# y el framework .NET, implementando arquitecturas escalables.</li>
                            <li><strong>ORM y Base de Datos:</strong> Implementación de Entity Framework para gestión eficiente de datos y consultas LINQ optimizadas.</li>
                            <li><strong>Aplicaciones Windows:</strong> Desarrollo de aplicaciones de escritorio con Windows Forms y tecnologías .NET MAUI.</li>
                            <li><strong>APIs REST:</strong> Desarrollo y consumo de servicios web RESTful utilizando ASP.NET Core.</li>
                            <li><strong>Debugging y optimización:</strong> Resolución de issues técnicos y optimización de rendimiento de aplicaciones.</li>
                        </ul>
                    </div>
                </div>

                <div class="experience-item">
                    <div class="job-title">QA Tester</div>
                    <div class="company">ASHPROGRAM (Consultora de Desarrollo de Software)</div>
                    <div class="job-description">
                        <ul>
                            <li><strong>Automatización de pruebas:</strong> Diseño y ejecución de pruebas automatizadas utilizando C# con Selenium WebDriver, mejorando la eficiencia del proceso de testing.</li>
                            <li><strong>Testing manual:</strong> Realización de pruebas funcionales y de regresión exhaustivas para garantizar la calidad del software.</li>
                            <li><strong>Testing de APIs:</strong> Utilización de Postman para pruebas de APIs REST, validando endpoints y respuestas.</li>
                            <li><strong>Documentación:</strong> Creación de casos de prueba detallados, planes de testing y documentación de defectos con seguimiento hasta su resolución.</li>
                            <li><strong>Colaboración:</strong> Trabajo estrecho con equipos de desarrollo para asegurar la calidad y funcionalidad del software.</li>
                        </ul>
                    </div>
                </div>

                <div class="experience-item">
                    <div class="job-title">Desarrollador Web</div>
                    <div class="company">Proyecto Institucional</div>
                    <div class="job-description">
                        <ul>
                            <li><strong>Mantenimiento web:</strong> Actualización y mantenimiento continuo de la página web institucional.</li>
                            <li><strong>Mejoras de UX/UI:</strong> Implementación de mejoras en la interfaz de usuario para optimizar la experiencia del usuario.</li>
                            <li><strong>Optimización:</strong> Mejoras en el rendimiento web y optimización de código.</li>
                            <li><strong>Desarrollo de funcionalidades:</strong> Creación de nuevas características y módulos según requerimientos.</li>
                            <li><strong>Soporte técnico:</strong> Provisión de soporte técnico continuo y resolución de incidencias.</li>
                        </ul>
                    </div>
                </div>
            </div>

            <div class="main-section">
                <h2 class="main-section-title">Formación Académica</h2>
                
                <div class="education-item">
                    <div class="degree">Técnico Superior en Desarrollo de Software</div>
                    <div class="institution">En curso</div>
                </div>

                <div class="education-item">
                    <div class="degree">Bachiller Técnico en Desarrollo de Software</div>
                    <div class="institution">Completado</div>
                </div>
            </div>

            <div class="main-section">
                <h2 class="main-section-title">Competencias Profesionales</h2>
                <div class="soft-skills">
                    <div class="soft-skill-item">
                        <div class="soft-skill-title">Resolución de Problemas</div>
                        <div class="soft-skill-desc">Análisis y solución eficiente de problemas técnicos complejos</div>
                    </div>
                    <div class="soft-skill-item">
                        <div class="soft-skill-title">Trabajo en Equipo</div>
                        <div class="soft-skill-desc">Colaboración efectiva en proyectos multidisciplinarios</div>
                    </div>
                    <div class="soft-skill-item">
                        <div class="soft-skill-title">Gestión del Tiempo</div>
                        <div class="soft-skill-desc">Capacidad para manejar múltiples tareas y proyectos simultáneamente</div>
                    </div>
                    <div class="soft-skill-item">
                        <div class="soft-skill-title">Comunicación Efectiva</div>
                        <div class="soft-skill-desc">Comunicación clara con equipos técnicos y no técnicos</div>
                    </div>
                    <div class="soft-skill-item">
                        <div class="soft-skill-title">Atención al Detalle</div>
                        <div class="soft-skill-desc">Precisión fundamental para la detección de errores y testing</div>
                    </div>
                    <div class="soft-skill-item">
                        <div class="soft-skill-title">Adaptabilidad</div>
                        <div class="soft-skill-desc">Capacidad de aprender nuevas tecnologías rápidamente</div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</body>
</html>
