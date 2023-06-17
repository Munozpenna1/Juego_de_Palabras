# Juego_de_Palabras
## El juego de palabras que vamos a presentar como grupo es:

```import random
a=(int(input("seleccione por favor un idioma:1(Español)\nChose a language: 2.(English)\nsi prega di selezionare una lingua:3(Italian)\nBitte wähle eine Sprache:4(German)\nveuillez sélectionner une langue:5(France)\nselecione um idioma:\nkérjük válasszon nyelvet:6(Hungarian)")))
if a == 1:
    b=(int(input("Por favor seleccione una dificultad:\n1.facil\n2.medio\n3.dificil" )))
    if b == 1:

        lista = [' Compañerismo', ' Galleta', ' Abrazo', 'Lealtad', 'Enriquecedor', ' Otoño', 'Ambición', 'Brillante', 'Quietus', ' Ciencia', ' Rojo', ' Lápiz', 'Canela', 'Aire', 'Amor', ' Autopista', ' Paciencia', 'Soledad', 'Estrategia', 'Avance', ' Moda', 'Crecimiento', 'Tenacidad', 'Emocionado', ' Literatura', 'Fiesta', ' Esperanza', 'Inspirador', ' Innovación', 'Creatividad', 'Electrizante', 'Embelesamiento', 'Carne', ' Reloj', ' Silencio', 'Rumbo', 'Nieve', 'Reverencia', 'Capacidad', 'Sueño', ' Naranja', 'Maravillarse', 'Cordialidad', 'Cambio', 'Computadora', 'Música', ' Uva', 'Epifanía', 'Correr', 'Agradecimiento', ' Liderazgo', ' Misterio', ' Gafas', 'Comunicación', 'Revelación', 'Aclamado', ' Lágrimas', 'Innovador', 'Susurro', ' Nieve', ' Horizonte', ' Marcador', ' Descubrimiento', 'Estilo', 'Embelesador', ' Deporte', 'Literatura', 'Sanar', 'Serenidad', ' Canino', 'Refrescante', 'Maravilla', 'Oficina', 'Relajación', ' Estilo', 'Vitalidad', 'Conservación', ' Dignidad', 'Redención', ' Natación', ' Descanso', 'Excitante', 'Profesión', ' Avena', ' Logro', 'Aplaudido', 'Tiempo', ' Yogur', ' Océano', 'Cine', 'Pueblo', ' Satisfacción', 'Café', ' Guitarra', 'Agua', ' Tiza', 'Responsabilidad', 'Prestigio', ' Placer', ' Llanto', 'Optimismo', 'Equipo', ' Igualdad', ' Vainilla', ' Baile', ' Autobús', 'Hobby', 'Imaginación', 'Irresistible', 'Resplandor', 'Adaptabilidad', 'Apreciación', ' Bolígrafo', ' Voluntariado', ' Esperanza ', 'Intrigante', 'Iluminador', 'Edificante', 'Impresionismo', ' Martes', ' Arquitectura', 'Progreso', 'Estrellas', ' Comunidad', 'Transcendental', 'Esplendoroso', 'Colina', 'Medio ambiente', ' Refresco', 'Anochecer', ' Inocencia', 'Maíz', ' Coraje', 'Sorprendido', ' Ejercicio', 'Espera', ' Fotografía', 'Realidad', ' Agradable', 'Encantamiento', ' Anochecer', ' Desierto', 'Impresionado', ' Triste', ' Aceite', 'Euforia', ' Pintura', ' Bienestar', ' Aldea', ' Resplandor', 'Reflexión', ' Danza', 'Pluma', 'Dedicación', 'Delicia', ' Risa', 'Enamoramiento', ' Pastel', 'Deporte', 'Reinvención', ' Cacao', ' Gastronomía', 'Simetría', 'Fraternidad', ' Ingeniero', 'Satisfactorio', 'Cacao', 'Aspiración', 'Autenticidad', 'Humildad', 'Intriga', 'Placer', 'Conciencia', 'Exhilarante', 'Abogado', ' Dinero', 'Yogur', 'Unidad', ' Computadora', ' Jugo', ' Fuego', 'Retroceso', 'Fascinación', 'Planeta', ' Felicidad', ' Gato', 'Grandeza', ' Elefante', 'Dulce', ' Conejo', 'Llanura', ' Amargo', ' Agua', ' Libro', ' Invierno', ' Trabajo', 'Atractivo', ' Optimismo', ' Escultura', 'Gastronomía', ' Bello', 'Gafas', ' Fútbol', 'Prodigio', ' Experiencia', 'Inspírate', ' Mar', ' Místico', ' Naturaleza', ' Escribir', ' Fantasía', ' Caminar', ' Alegría', 'Universo', ' Te', 'Expresión', ' Carcajada', 'Espiritualidad', 'Rejuvenecimiento', ' Río', 'Felicidad', 'banana', ' Yoga', 'Emocional', 'Oportunidad', 'Casa', ' Lapiz', 'Paciencia', ' Carretera', 'Gozo', ' Confianza', 'Atracción', 'Soñar', 'Impresionante', ' Cumpleaños', 'Pesadilla', 'Asombro', ' Nubes', 'Maravilloso', 'Equilibrio', ' Colaboración', 'Espacio', ' Empoderamiento', 'Diseño', ' Estudio', 'Emocionalmente', ' Resiliencia', 'Baloncesto', 'Resplandeciente', ' Empatía', 'Interiores', 'Estupor', 'Inolvidable', 'Admiración', ' Hermoso', 'Montaña', 'Realización', ' Ácido', 'Escribir', 'Abrazo', 'Cerámica', ' Saltar', 'Accion', ' Suspiro', 'Enojo', 'Mesa', ' Sombrero', ' Motocicleta', 'Cerveza', ' Zapatos', 'Verdad', 'Apasionantemente', 'Estrella', ' Vacaciones', 'Ritmo', ' Cielo', 'Pasatiempo', ' Colorido', 'Viajes', ' Rocío', 'Prodigioso', ' Psicología', 'Amanecer', ' Gratitud', ' Desafío', ' Nadar', 'Análisis', 'Exquisito', ' Patrimonio', ' Televisión', ' Pantalón', ' Regalo', 'Recompensa', 'Desierto', ' Nobleza', 'Conexión', ' Cuento', 'Escuela', ' Madurez', ' Lluvia', 'Lámpara', 'Espontaneidad', ' Claro', 'Constelación', ' Mouse', 'Cultura', ' Fresco', ' Inspiración', ' Sol Guitarra', 'Libro', ' Diversidad', 'Riesgo', 'naranja', 'Universidad', ' Determinación', ' Festival', ' Amabilidad', ' Brisa', ' Hámster ', 'Autopista', ' Maravilla', 'Abeja', 'Esperanza', ' Conocimiento', ' Colina', ' Hámster', ' Gentil', ' Energía', ' Radiante', ' Medicina', 'Natación', ' Cascada', ' Cariñoso', ' Cálido', 'Amistad', ' Teléfono', 'Conejo', ' Lunes', 'Aire libre', 'Carretera', ' Luminoso', ' Saxofón', 'Ética', ' Tenis', ' Camión', 'Aprendizaje', 'Sinceridad', ' Sostenibilidad', ' Bondad', 'Selva', 'Luminosidad', 'Enfoque', ' Perro', ' Universidad', ' Crianza', 'Descubrimiento', ' Jardín', 'Destreza', 'Tren', ' Iluminación', 'Planificación', ' Arena', 'Tenis', ' Exuberante', 'Superación', ' Verano', 'Ingeniero', ' Bosque', 'Tormenta', 'Trascendencia', 'Divorciado', 'Armonía', 'Empatía', ' Respeto', 'Reloj', ' Amigo', 'Hilo', ' Yogurt', ' Colegio', 'Serendipia', 'Avión', ' Juego', 'Risas', ' Plenitud', 'Escultura', 'Hospital', ' Sonrisa', 'Cautivador', 'Intuición', 'Experiencia', 'Esplendor', 'Océano', 'Prosperidad', 'Consciencia', ' Tequila', 'Aniversario', 'Seducción', 'Liderazgo', 'Sobresaliente', ' Cortés', 'Renovación', ' Valle', 'Mañana', 'Noche', 'Invierno', 'Carisma', 'Evolución', ' Flexibilidad', ' Enérgico', ' Cambio', ' Baloncesto', ' Profesionalismo', 'Inspiração', 'Emocionante', ' Maravilloso', 'Éxito', 'Solidaridad', 'Renacimiento', ' Verdura', ' Vestido', ' Conchas', 'Mar', ' Médico', 'Fe', 'Camiseta', ' Creatividad', 'Amargo', ' Celebración', ' Vitalidad', ' Flores', ' Noche', 'Risueño', 'Gratificación', ' Aventura', ' Pimienta', 'Primavera', 'Estimulante', ' Techo', 'Azúcar', 'Vestido', ' Calma', ' Libertad', ' Tranquilidad', ' Consciencia', ' Aniversario', 'Momentos', ' Feliz', ' Galaxia', ' Autenticidad', ' Meditación', ' Competencia', ' Árbol', 'Nutrición', 'Glorioso', 'Ciencia', 'Elevación', ' Aire', ' Justicia', 'Eficiencia', ' Encanto', 'Fuego', ' Tradición', ' Oasis', 'Sorpresa', 'Enseñanza', 'Júbilo', ' Soñar', 'Desbordante', 'Aventura', 'Televisión', 'Zapatos', ' Chocolate', 'Perro', 'Inspiración', ' Boda', ' Enojo', 'Apasionado', 'Medicina', ' Cepillo', 'Claridad', 'Envolvente', ' Pizza', 'Luna', 'Justicia', 'Empoderamiento', 'Silla', 'Desbordado', ' Viento', 'Riqueza', 'Recuerdos', ' Entusiasmo', ' Tecnología', ' Tienda', 'Galaxia', 'Magia', ' Encantador', ' Pasta', 'Exuberancia', 'Equidad', ' Cine', 'Perseverancia', 'Organización', ' Perseverancia', 'Carrera', 'Estupefacto', 'Sueños', 'Originalidad', 'Extraordinario', ' Trascendental', ' Oficina', ' Llanura', 'Leche', ' Patineta', ' Celular', 'Inteligencia', ' Relajante', ' Sonido', 'Arrebato', ' Atardecer', ' Inspirador', 'Caminar', ' Serenidad', 'Fantasía', 'Emancipador', ' Atento', ' Helado', 'Tarde', 'Lápiz', ' Pertenencia', 'Emprendimiento', 'Integridad', 'Inocencia', 'Harmonía', 'Autoestima', 'Alegría', ' Té', 'Cuaderno', 'Pintura', 'Arroz', 'Enriquecimiento', 'Motivador', 'Inclusión', 'manzana', ' Mindfulness', 'Respeto', ' Exploración', ' Vecino', ' Riqueza', 'Transformación', ' Pintar', ' Gozo', 'Caos', ' Tierra', 'Mariposa', ' Admiración', ' Exótico', 'Sostenibilidad', ' Apasionado', 'Vainilla', 'Fascinador', 'Ácido', 'Tigre', ' Tristeza', 'Visión', 'Relámpago', 'Satélite', ' Sincero', 'Celular', 'Verdura', 'Revigorizante', ' Whisky', 'Teatro', 'Paisaje', 'Sensación', 'Fortaleza', ' Calle', 'Puerta', ' Carne', 'Misterio', ' Teatro', 'Pasta', ' Sábado', 'Compromiso', 'Triunfo', ' Fascinante', 'Valentía', ' Trigo', 'Amabilidad', 'Paz', 'Sustentabilidad', 'Persistencia', ' Ciudad', 'Arquitectura', ' Fiesta', 'Soñador', ' Enfermería', ' Fortaleza', 'Suspiro', ' Tierno', ' Humildad', ' Escalar', ' Manzana', ' Coche', 'Luminoso', ' Soltero', 'Relaciones', 'Alegre', 'Revitalizante', ' Amistoso', 'Emocionadamente', 'Avenida', ' Belleza', ' Amarillo', 'Desafío', ' Cultura', ' Eficiencia', ' Batería', ' Majestuoso', ' Escáner', 'Sal', ' Compañero', ' Familia', 'Vibrante', ' Medio Ambiente', ' Aprendizaje', ' Abogado', 'Entretenimiento', 'Valores', 'Tienda', ' Aceptación', 'Familia', 'Conocimiento', 'Fuerza', 'Espíritu', ' Valiente', 'Revolución', 'Cuidado', ' Explorador', 'Playa', ' Sofá', ' Amistad', 'Autobús', 'Pescado', 'Danza', ' Encantamiento', ' Montaña', 'Bosque', 'Sobrevivencia', 'Incomparable', ' Hospital', ' Jardin', ' Leyenda', ' Avenida', 'Sublimación', ' Ensalada', 'Destino', ' Amable', ' Dulce', 'Eternidad', 'Sombrero', ' Eterno', ' Amoroso', 'Pintar', 'Corazón', 'Constancia', ' Silla', 'Maestro', ' Automóvil', ' Metrópoli', ' Vibrante', 'Té', 'Subyugado', 'Cepillo', ' Harmonía', 'Plenitud', 'Adictivo', ' Violín', ' Meta', 'Pletórico', 'Pensamiento', ' Lámpara', ' Disfrute', 'Ingenio', 'Retos', 'Alucinante', 'Trabajo', ' Playa', ' Refugio', ' Mañana', ' Enojado', ' Honestidad', 'Fantástico', ' Cautivador', ' Sorprendido', ' Transformación', 'Verano', ' Matemáticas', ' Sosiego', ' Moto', ' León', ' Confort', ' Recuerdo', 'Compañía', 'Gota', ' Sueño', 'Conmovedor', 'Desarrollo', 'Sabiduría', ' Casado', 'Casado', ' Amor', 'Moda', ' Arte', ' Heroico', 'Médico', 'Recuerdo', 'Trascendental', 'Autonomía', 'Techo', 'Filosofía', 'Asombroso', 'Sororidad', ' Papel', 'Tolerancia', ' Pared', ' Escuela', 'Escalar', ' Azúcar', 'Igualdad', ' Tarde', 'Refresco', 'Futuro', ' Paraíso', 'Ingeniería', 'Sublime', 'Descanso', 'Mantequilla', ' Romance', 'Mediodía', ' Rayo', ' Generoso', 'Motivación', 'Voluntad', 'Viudo', ' Ingeniería', ' Amanecer', 'Pared', 'Vivacidad', 'Exteriores', ' Independencia', 'Elefante', ' Viudo', ' Mediodía', 'Feliz', 'Maravillar', 'Embriagador', 'Prometedor', ' Educación', ' Sushi', ' Paciente', 'Innovación', 'Agricultura', 'Determinación', ' Trueno', 'Energía', 'Libélula', 'Increíble', 'Solución', 'Rayo', ' Tigre', 'Gato', ' Dedicación', ' Barco', 'Exaltación', 'Enjuague', 'Pasión', ' Ecología', 'Honestidad', ' Emoción', ' Correr', 'Tecnología', 'Revelador', 'Explorar', 'Deslumbramiento', 'Despertar', ' Vino', 'Tristeza', ' Historia', ' Luna', 'Estudio', ' Salud', ' Sabiduría', 'Exorbitante', 'Encantador', ' Leche', 'Metas', 'Bufanda', 'Nadar', 'Arte', 'Valle', 'Río', ' Natura', ' Hamburguesa', 'Historia', 'Bienestar', ' Bendición', 'Diversión', 'Exploración', 'Naturaleza', 'Inquietud', 'Melodía', ' Filantropía', ' Bufanda', 'Vigorizante', 'Cantar', ' Tolerancia', ' Gota', 'Mirada', 'Descubrir', ' Sal', ' Diversión', 'Ciudad', ' Perdón', ' Pueblo', 'Serendipidad', ' Solidaridad', ' Domingo', 'Herencia', 'Fútbol', 'Comunidad', 'Magnífico', ' Arcoíris', ' Estímulo', 'Disciplina', ' Guardería', 'Estupendo', 'Anhelo', ' Entrega', ' Música', 'Provechoso', 'Salud', ' Puerta', ' Negocios', ' Ventana', 'Sensibilidad', ' Tren', ' Estabilidad', ' Jirafa', 'Enigma', ' Valentía', 'Jugo', ' Magia', 'Palabra', ' Único', ' Piano', ' Metrópolis', 'Productividad', 'Regocijo', ' Pintoresco', 'Metrópolis', ' Renovador', 'Estremecimiento', 'Viaje', 'Coraje', 'Estremecedor', ' Cantar', 'Celebración', 'Cooperación', ' Bailar', ' Enjuague', 'Embeleso', 'Religión', ' Idílico', 'Generación', 'Trascendente', ' Pluma', 'Trigo', 'Satisfacción', 'Negocio', ' Reptil', 'Fruta', ' Mesa', ' Organización', ' Estrellas', ' Impresora', 'Meta', ' Motivación', 'Intrepidez', ' Equilibrio', 'Tranquilidad', 'Cumpleaños', ' Divorciado', 'Brillo', 'Colaboración', ' Verde', ' Postre', 'Melancolía', 'Fotografía', 'Risa', 'Aroma', ' Fruta', ' Relajación', 'Rocío', 'Vigor', ' Generosidad', 'Sonrisa', 'Otoño', 'Impulso', 'Encanto', 'Subyugante', ' Salado', ' Lucidez', ' Azul', 'Entusiasmo', 'Belleza', ' Crecimiento', ' Azucar', 'Aceite', 'Arcoíris', ' Viaje', 'Hámster', ' Sorpresa', ' Aventurero', ' Café', 'Sorprendente', 'Curiosidad', ' Hilo', ' Pescado', 'Notable', ' Comprensión', ' Mantequilla', 'Madrugada', 'Estudiante', ' Primavera', ' Lago', ' Terapia', 'Habilidad', 'Gracia', 'Inigualable', 'Propósito', ' Beso', ' Felino', 'Soltero', ' Paz', ' Técnico', 'pera', 'Bailar', 'Colibrí', ' Avión', 'Lago', 'Embriagante', 'Eufórico', 'Apasionante', 'Festividad', ' Sol', 'Pantalón', 'Saltar', 'Barco', ' Cerámica', ' Interdependencia', ' Jugar', 'Elocuencia', 'Estimulado', 'Esencia', 'Salado', 'Confianza', 'Avena', ' Ética', 'Iniciativa', ' Platano', ' Nube', 'Exuberante', ' Escribir ', 'Encuentro', ' Nutrición', 'Deseo', ' Noble', ' Espiritualidad', ' Cooperación', ' Armonía', 'Pimienta', ' Superación', ' Sublime', 'Deslumbrante', 'Tradición', 'Flexibilidad', ' Universo', 'Jirafa', 'Calle', 'Diversidad', ' Actuar', ' Sensible', 'Técnico', 'Compasión', 'Espectacular', ' Arroz', ' Ave', ' Cuaderno', 'Genuino', 'Silencio', ' Queso', ' Camiseta', ' Madrugada', 'Abundancia', 'Compañerismo', 'Desafiante', 'Astonante', 'Impresión', ' Instituto', 'Atardecer', 'Logro', ' Tablet', ' Tormenta', ' Emprendimiento', 'Trueno', 'Excentricidad', 'Aldea', 'Sentimientos', 'Electrizado', 'Fascinante', 'Gratitud', ' Canela', 'Victoria', ' Lealtad', ' Bicicleta', ' Maíz', ' Éxito', 'Emoción', 'Educación', 'Cascada', 'Libertad', ' Odontología', ' Integridad', 'Sofá', 'Investigación', 'Queso', 'Iluminación', 'Generosidad', ' Pasión', 'Tierra', ' Poesía', 'Sacrificio', 'Resiliencia', 'Maravillosamente', 'Enérgico', 'Ventana']



        def Palabra_Aleatoria(lista_palabras):
            palabra_aleatoria = random.choice(lista_palabras)
            return palabra_aleatoria

        def ocultar_palabra(palabra):
            oculta = "_" * len(palabra)
            return oculta

        def mostrar_palabra(palabra_oculta):
            print("Palabra:", " ".join(palabra_oculta))

        def adivinar_letra():
            return input("Adivina una letra: ")

        def Stickman(intentos):
            if intentos == range(1, 1000):
                print("")
                print("")
                print("")
                print("")
                print("")
                print("")
                print("=====")

        def jugar_ahorcado():
            palabra = Palabra_Aleatoria(lista)
            palabra_oculta = ocultar_palabra(palabra)
            intentos_totales = 1000
            intentos_restantes = intentos_totales


            while intentos_restantes > 0:
                mostrar_palabra(palabra_oculta)
                Stickman(intentos_restantes)
                letra = adivinar_letra()
                acierto = False
                nueva_palabra_oculta = ""

                for i in range(len(palabra)):
                    if palabra[i].lower() == letra.lower():
                        nueva_palabra_oculta += letra
                        acierto = True
                    else:
                        nueva_palabra_oculta += palabra_oculta[i]

                if acierto:
                    palabra_oculta = nueva_palabra_oculta
                    print("¡Correcto!")

                else:
                    intentos_restantes -= 1
                    print("Incorrecto. Te quedan", intentos_restantes, "intentos.")

                if palabra_oculta.lower() == palabra.lower():
                    print("¡Ganaste! Has adivinado la palabra:", palabra)
                    break

            if intentos_restantes == 0:
                    print("¡Perdiste! La palabra era:", palabra)



        jugar_ahorcado()
        
    elif b == 2:


        lista = ['Compañerismo', 'Galleta', 'Abrazo', 'Lealtad', 'Enriquecedor', 'Otoño', 'Ambición', 'Brillante', 'Quietus', 'Ciencia', 'Rojo', 'Lápiz']

        def Palabra_Aleatoria(lista_palabras):
            palabra_aleatoria = random.choice(lista_palabras)
            return palabra_aleatoria

        def ocultar_palabra(palabra):
            oculta = "_" * len(palabra)
            return oculta

        def mostrar_palabra(palabra_oculta):
            print("Palabra:", " ".join(palabra_oculta))

        def adivinar_letra():
            return input("Adivina una letra: ")

        def Stickman(intentos):
            if intentos == 0:
                print("  -------")
                print("  |     |")
                print("  |     O")
                print("  |    /|\\")
                print("  |    / \\")
                print("  |")
                print("=====")
            elif intentos == 1:
                print("  -------")
                print("  |     |")
                print("  |     O")
                print("  |    /|\\")
                print("  |    /")
                print("  |")
                print("=====")
            elif intentos == 2:
                print("  -------")
                print("  |     |")
                print("  |     O")
                print("  |    /|\\")
                print("  |")
                print("  |")
                print("=====")
            elif intentos == 3:
                print("  -------")
                print("  |     |")
                print("  |     O")
                print("  |     |\\")
                print("  |")
                print("  |")
                print("=====")
            elif intentos == 4:
                print("  -------")
                print("  |     |")
                print("  |     O")
                print("  |     |")
                print("  |")
                print("  |")
                print("=====")
            elif intentos == 5:
                print("  -------")
                print("  |     |")
                print("  |     O")
                print("  |")
                print("  |")
                print("  |")
                print("=====")
            elif intentos == 6:
                print("  -------")
                print("  |     |")
                print("  |")
                print("  |")
                print("  |")
                print("  |")
                print("=====")
            elif intentos == 7:
                print("  -------")
                print("  |")
                print("  |")
                print("  |")
                print("  |")
                print("  |")
                print("=====")
            elif intentos == 8:
                print("  |")
                print("  |")
                print("  |")
                print("  |")
                print("  |")
                print("=====")
            elif intentos == 9:
                print("")
                print("")
                print("")
                print("")
                print("")
                print("")
                print("=====")
            elif intentos == 10:
                print("")
                print("")
                print("")
                print("")
                print("")
                print("")
                print("=====")

        def jugar_ahorcado():
            palabra = Palabra_Aleatoria(lista)
            palabra_oculta = ocultar_palabra(palabra)
            intentos_totales = 10
            intentos_restantes = intentos_totales


            while intentos_restantes > 0:
                mostrar_palabra(palabra_oculta)
                Stickman(intentos_restantes)
                letra = adivinar_letra()
                acierto = False
                nueva_palabra_oculta = ""

                for i in range(len(palabra)):
                    if palabra[i].lower() == letra.lower():
                        nueva_palabra_oculta += letra
                        acierto = True
                    else:
                        nueva_palabra_oculta += palabra_oculta[i]

                if acierto:
                    palabra_oculta = nueva_palabra_oculta
                    print("¡Correcto!")

                else:
                    intentos_restantes -= 1
                    print("Incorrecto. Te quedan", intentos_restantes, "intentos.")

                if palabra_oculta.lower() == palabra.lower():
                    print("¡Ganaste! Has adivinado la palabra:", palabra)
                    break

                if intentos_restantes == 0:
                    print("¡Perdiste! La palabra era:", palabra)



        jugar_ahorcado()


    elif b == 3:
        lista = [' Compañerismo', ' Galleta', ' Abrazo', 'Lealtad', 'Enriquecedor', ' Otoño', 'Ambición', 'Brillante', 'Quietus', ' Ciencia', ' Rojo', ' Lápiz', 'Canela', 'Aire', 'Amor', ' Autopista', ' Paciencia', 'Soledad', 'Estrategia', 'Avance', ' Moda', 'Crecimiento', 'Tenacidad', 'Emocionado', ' Literatura', 'Fiesta', ' Esperanza', 'Inspirador', ' Innovación', 'Creatividad', 'Electrizante', 'Embelesamiento', 'Carne', ' Reloj', ' Silencio', 'Rumbo', 'Nieve', 'Reverencia', 'Capacidad', 'Sueño', ' Naranja', 'Maravillarse', 'Cordialidad', 'Cambio', 'Computadora', 'Música', ' Uva', 'Epifanía', 'Correr', 'Agradecimiento', ' Liderazgo', ' Misterio', ' Gafas', 'Comunicación', 'Revelación', 'Aclamado', ' Lágrimas', 'Innovador', 'Susurro', ' Nieve', ' Horizonte', ' Marcador', ' Descubrimiento', 'Estilo', 'Embelesador', ' Deporte', 'Literatura', 'Sanar', 'Serenidad', ' Canino', 'Refrescante', 'Maravilla', 'Oficina', 'Relajación', ' Estilo', 'Vitalidad', 'Conservación', ' Dignidad', 'Redención', ' Natación', ' Descanso', 'Excitante', 'Profesión', ' Avena', ' Logro', 'Aplaudido', 'Tiempo', ' Yogur', ' Océano', 'Cine', 'Pueblo', ' Satisfacción', 'Café', ' Guitarra', 'Agua', ' Tiza', 'Responsabilidad', 'Prestigio', ' Placer', ' Llanto', 'Optimismo', 'Equipo', ' Igualdad', ' Vainilla', ' Baile', ' Autobús', 'Hobby', 'Imaginación', 'Irresistible', 'Resplandor', 'Adaptabilidad', 'Apreciación', ' Bolígrafo', ' Voluntariado', ' Esperanza ', 'Intrigante', 'Iluminador', 'Edificante', 'Impresionismo', ' Martes', ' Arquitectura', 'Progreso', 'Estrellas', ' Comunidad', 'Transcendental', 'Esplendoroso', 'Colina', 'Medio ambiente', ' Refresco', 'Anochecer', ' Inocencia', 'Maíz', ' Coraje', 'Sorprendido', ' Ejercicio', 'Espera', ' Fotografía', 'Realidad', ' Agradable', 'Encantamiento', ' Anochecer', ' Desierto', 'Impresionado', ' Triste', ' Aceite', 'Euforia', ' Pintura', ' Bienestar', ' Aldea', ' Resplandor', 'Reflexión', ' Danza', 'Pluma', 'Dedicación', 'Delicia', ' Risa', 'Enamoramiento', ' Pastel', 'Deporte', 'Reinvención', ' Cacao', ' Gastronomía', 'Simetría', 'Fraternidad', ' Ingeniero', 'Satisfactorio', 'Cacao', 'Aspiración', 'Autenticidad', 'Humildad', 'Intriga', 'Placer', 'Conciencia', 'Exhilarante', 'Abogado', ' Dinero', 'Yogur', 'Unidad', ' Computadora', ' Jugo', ' Fuego', 'Retroceso', 'Fascinación', 'Planeta', ' Felicidad', ' Gato', 'Grandeza', ' Elefante', 'Dulce', ' Conejo', 'Llanura', ' Amargo', ' Agua', ' Libro', ' Invierno', ' Trabajo', 'Atractivo', ' Optimismo', ' Escultura', 'Gastronomía', ' Bello', 'Gafas', ' Fútbol', 'Prodigio', ' Experiencia', 'Inspírate', ' Mar', ' Místico', ' Naturaleza', ' Escribir', ' Fantasía', ' Caminar', ' Alegría', 'Universo', ' Te', 'Expresión', ' Carcajada', 'Espiritualidad', 'Rejuvenecimiento', ' Río', 'Felicidad', 'banana', ' Yoga', 'Emocional', 'Oportunidad', 'Casa', ' Lapiz', 'Paciencia', ' Carretera', 'Gozo', ' Confianza', 'Atracción', 'Soñar', 'Impresionante', ' Cumpleaños', 'Pesadilla', 'Asombro', ' Nubes', 'Maravilloso', 'Equilibrio', ' Colaboración', 'Espacio', ' Empoderamiento', 'Diseño', ' Estudio', 'Emocionalmente', ' Resiliencia', 'Baloncesto', 'Resplandeciente', ' Empatía', 'Interiores', 'Estupor', 'Inolvidable', 'Admiración', ' Hermoso', 'Montaña', 'Realización', ' Ácido', 'Escribir', 'Abrazo', 'Cerámica', ' Saltar', 'Accion', ' Suspiro', 'Enojo', 'Mesa', ' Sombrero', ' Motocicleta', 'Cerveza', ' Zapatos', 'Verdad', 'Apasionantemente', 'Estrella', ' Vacaciones', 'Ritmo', ' Cielo', 'Pasatiempo', ' Colorido', 'Viajes', ' Rocío', 'Prodigioso', ' Psicología', 'Amanecer', ' Gratitud', ' Desafío', ' Nadar', 'Análisis', 'Exquisito', ' Patrimonio', ' Televisión', ' Pantalón', ' Regalo', 'Recompensa', 'Desierto', ' Nobleza', 'Conexión', ' Cuento', 'Escuela', ' Madurez', ' Lluvia', 'Lámpara', 'Espontaneidad', ' Claro', 'Constelación', ' Mouse', 'Cultura', ' Fresco', ' Inspiración', ' Sol Guitarra', 'Libro', ' Diversidad', 'Riesgo', 'naranja', 'Universidad', ' Determinación', ' Festival', ' Amabilidad', ' Brisa', ' Hámster ', 'Autopista', ' Maravilla', 'Abeja', 'Esperanza', ' Conocimiento', ' Colina', ' Hámster', ' Gentil', ' Energía', ' Radiante', ' Medicina', 'Natación', ' Cascada', ' Cariñoso', ' Cálido', 'Amistad', ' Teléfono', 'Conejo', ' Lunes', 'Aire libre', 'Carretera', ' Luminoso', ' Saxofón', 'Ética', ' Tenis', ' Camión', 'Aprendizaje', 'Sinceridad', ' Sostenibilidad', ' Bondad', 'Selva', 'Luminosidad', 'Enfoque', ' Perro', ' Universidad', ' Crianza', 'Descubrimiento', ' Jardín', 'Destreza', 'Tren', ' Iluminación', 'Planificación', ' Arena', 'Tenis', ' Exuberante', 'Superación', ' Verano', 'Ingeniero', ' Bosque', 'Tormenta', 'Trascendencia', 'Divorciado', 'Armonía', 'Empatía', ' Respeto', 'Reloj', ' Amigo', 'Hilo', ' Yogurt', ' Colegio', 'Serendipia', 'Avión', ' Juego', 'Risas', ' Plenitud', 'Escultura', 'Hospital', ' Sonrisa', 'Cautivador', 'Intuición', 'Experiencia', 'Esplendor', 'Océano', 'Prosperidad', 'Consciencia', ' Tequila', 'Aniversario', 'Seducción', 'Liderazgo', 'Sobresaliente', ' Cortés', 'Renovación', ' Valle', 'Mañana', 'Noche', 'Invierno', 'Carisma', 'Evolución', ' Flexibilidad', ' Enérgico', ' Cambio', ' Baloncesto', ' Profesionalismo', 'Inspiração', 'Emocionante', ' Maravilloso', 'Éxito', 'Solidaridad', 'Renacimiento', ' Verdura', ' Vestido', ' Conchas', 'Mar', ' Médico', 'Fe', 'Camiseta', ' Creatividad', 'Amargo', ' Celebración', ' Vitalidad', ' Flores', ' Noche', 'Risueño', 'Gratificación', ' Aventura', ' Pimienta', 'Primavera', 'Estimulante', ' Techo', 'Azúcar', 'Vestido', ' Calma', ' Libertad', ' Tranquilidad', ' Consciencia', ' Aniversario', 'Momentos', ' Feliz', ' Galaxia', ' Autenticidad', ' Meditación', ' Competencia', ' Árbol', 'Nutrición', 'Glorioso', 'Ciencia', 'Elevación', ' Aire', ' Justicia', 'Eficiencia', ' Encanto', 'Fuego', ' Tradición', ' Oasis', 'Sorpresa', 'Enseñanza', 'Júbilo', ' Soñar', 'Desbordante', 'Aventura', 'Televisión', 'Zapatos', ' Chocolate', 'Perro', 'Inspiración', ' Boda', ' Enojo', 'Apasionado', 'Medicina', ' Cepillo', 'Claridad', 'Envolvente', ' Pizza', 'Luna', 'Justicia', 'Empoderamiento', 'Silla', 'Desbordado', ' Viento', 'Riqueza', 'Recuerdos', ' Entusiasmo', ' Tecnología', ' Tienda', 'Galaxia', 'Magia', ' Encantador', ' Pasta', 'Exuberancia', 'Equidad', ' Cine', 'Perseverancia', 'Organización', ' Perseverancia', 'Carrera', 'Estupefacto', 'Sueños', 'Originalidad', 'Extraordinario', ' Trascendental', ' Oficina', ' Llanura', 'Leche', ' Patineta', ' Celular', 'Inteligencia', ' Relajante', ' Sonido', 'Arrebato', ' Atardecer', ' Inspirador', 'Caminar', ' Serenidad', 'Fantasía', 'Emancipador', ' Atento', ' Helado', 'Tarde', 'Lápiz', ' Pertenencia', 'Emprendimiento', 'Integridad', 'Inocencia', 'Harmonía', 'Autoestima', 'Alegría', ' Té', 'Cuaderno', 'Pintura', 'Arroz', 'Enriquecimiento', 'Motivador', 'Inclusión', 'manzana', ' Mindfulness', 'Respeto', ' Exploración', ' Vecino', ' Riqueza', 'Transformación', ' Pintar', ' Gozo', 'Caos', ' Tierra', 'Mariposa', ' Admiración', ' Exótico', 'Sostenibilidad', ' Apasionado', 'Vainilla', 'Fascinador', 'Ácido', 'Tigre', ' Tristeza', 'Visión', 'Relámpago', 'Satélite', ' Sincero', 'Celular', 'Verdura', 'Revigorizante', ' Whisky', 'Teatro', 'Paisaje', 'Sensación', 'Fortaleza', ' Calle', 'Puerta', ' Carne', 'Misterio', ' Teatro', 'Pasta', ' Sábado', 'Compromiso', 'Triunfo', ' Fascinante', 'Valentía', ' Trigo', 'Amabilidad', 'Paz', 'Sustentabilidad', 'Persistencia', ' Ciudad', 'Arquitectura', ' Fiesta', 'Soñador', ' Enfermería', ' Fortaleza', 'Suspiro', ' Tierno', ' Humildad', ' Escalar', ' Manzana', ' Coche', 'Luminoso', ' Soltero', 'Relaciones', 'Alegre', 'Revitalizante', ' Amistoso', 'Emocionadamente', 'Avenida', ' Belleza', ' Amarillo', 'Desafío', ' Cultura', ' Eficiencia', ' Batería', ' Majestuoso', ' Escáner', 'Sal', ' Compañero', ' Familia', 'Vibrante', ' Medio Ambiente', ' Aprendizaje', ' Abogado', 'Entretenimiento', 'Valores', 'Tienda', ' Aceptación', 'Familia', 'Conocimiento', 'Fuerza', 'Espíritu', ' Valiente', 'Revolución', 'Cuidado', ' Explorador', 'Playa', ' Sofá', ' Amistad', 'Autobús', 'Pescado', 'Danza', ' Encantamiento', ' Montaña', 'Bosque', 'Sobrevivencia', 'Incomparable', ' Hospital', ' Jardin', ' Leyenda', ' Avenida', 'Sublimación', ' Ensalada', 'Destino', ' Amable', ' Dulce', 'Eternidad', 'Sombrero', ' Eterno', ' Amoroso', 'Pintar', 'Corazón', 'Constancia', ' Silla', 'Maestro', ' Automóvil', ' Metrópoli', ' Vibrante', 'Té', 'Subyugado', 'Cepillo', ' Harmonía', 'Plenitud', 'Adictivo', ' Violín', ' Meta', 'Pletórico', 'Pensamiento', ' Lámpara', ' Disfrute', 'Ingenio', 'Retos', 'Alucinante', 'Trabajo', ' Playa', ' Refugio', ' Mañana', ' Enojado', ' Honestidad', 'Fantástico', ' Cautivador', ' Sorprendido', ' Transformación', 'Verano', ' Matemáticas', ' Sosiego', ' Moto', ' León', ' Confort', ' Recuerdo', 'Compañía', 'Gota', ' Sueño', 'Conmovedor', 'Desarrollo', 'Sabiduría', ' Casado', 'Casado', ' Amor', 'Moda', ' Arte', ' Heroico', 'Médico', 'Recuerdo', 'Trascendental', 'Autonomía', 'Techo', 'Filosofía', 'Asombroso', 'Sororidad', ' Papel', 'Tolerancia', ' Pared', ' Escuela', 'Escalar', ' Azúcar', 'Igualdad', ' Tarde', 'Refresco', 'Futuro', ' Paraíso', 'Ingeniería', 'Sublime', 'Descanso', 'Mantequilla', ' Romance', 'Mediodía', ' Rayo', ' Generoso', 'Motivación', 'Voluntad', 'Viudo', ' Ingeniería', ' Amanecer', 'Pared', 'Vivacidad', 'Exteriores', ' Independencia', 'Elefante', ' Viudo', ' Mediodía', 'Feliz', 'Maravillar', 'Embriagador', 'Prometedor', ' Educación', ' Sushi', ' Paciente', 'Innovación', 'Agricultura', 'Determinación', ' Trueno', 'Energía', 'Libélula', 'Increíble', 'Solución', 'Rayo', ' Tigre', 'Gato', ' Dedicación', ' Barco', 'Exaltación', 'Enjuague', 'Pasión', ' Ecología', 'Honestidad', ' Emoción', ' Correr', 'Tecnología', 'Revelador', 'Explorar', 'Deslumbramiento', 'Despertar', ' Vino', 'Tristeza', ' Historia', ' Luna', 'Estudio', ' Salud', ' Sabiduría', 'Exorbitante', 'Encantador', ' Leche', 'Metas', 'Bufanda', 'Nadar', 'Arte', 'Valle', 'Río', ' Natura', ' Hamburguesa', 'Historia', 'Bienestar', ' Bendición', 'Diversión', 'Exploración', 'Naturaleza', 'Inquietud', 'Melodía', ' Filantropía', ' Bufanda', 'Vigorizante', 'Cantar', ' Tolerancia', ' Gota', 'Mirada', 'Descubrir', ' Sal', ' Diversión', 'Ciudad', ' Perdón', ' Pueblo', 'Serendipidad', ' Solidaridad', ' Domingo', 'Herencia', 'Fútbol', 'Comunidad', 'Magnífico', ' Arcoíris', ' Estímulo', 'Disciplina', ' Guardería', 'Estupendo', 'Anhelo', ' Entrega', ' Música', 'Provechoso', 'Salud', ' Puerta', ' Negocios', ' Ventana', 'Sensibilidad', ' Tren', ' Estabilidad', ' Jirafa', 'Enigma', ' Valentía', 'Jugo', ' Magia', 'Palabra', ' Único', ' Piano', ' Metrópolis', 'Productividad', 'Regocijo', ' Pintoresco', 'Metrópolis', ' Renovador', 'Estremecimiento', 'Viaje', 'Coraje', 'Estremecedor', ' Cantar', 'Celebración', 'Cooperación', ' Bailar', ' Enjuague', 'Embeleso', 'Religión', ' Idílico', 'Generación', 'Trascendente', ' Pluma', 'Trigo', 'Satisfacción', 'Negocio', ' Reptil', 'Fruta', ' Mesa', ' Organización', ' Estrellas', ' Impresora', 'Meta', ' Motivación', 'Intrepidez', ' Equilibrio', 'Tranquilidad', 'Cumpleaños', ' Divorciado', 'Brillo', 'Colaboración', ' Verde', ' Postre', 'Melancolía', 'Fotografía', 'Risa', 'Aroma', ' Fruta', ' Relajación', 'Rocío', 'Vigor', ' Generosidad', 'Sonrisa', 'Otoño', 'Impulso', 'Encanto', 'Subyugante', ' Salado', ' Lucidez', ' Azul', 'Entusiasmo', 'Belleza', ' Crecimiento', ' Azucar', 'Aceite', 'Arcoíris', ' Viaje', 'Hámster', ' Sorpresa', ' Aventurero', ' Café', 'Sorprendente', 'Curiosidad', ' Hilo', ' Pescado', 'Notable', ' Comprensión', ' Mantequilla', 'Madrugada', 'Estudiante', ' Primavera', ' Lago', ' Terapia', 'Habilidad', 'Gracia', 'Inigualable', 'Propósito', ' Beso', ' Felino', 'Soltero', ' Paz', ' Técnico', 'pera', 'Bailar', 'Colibrí', ' Avión', 'Lago', 'Embriagante', 'Eufórico', 'Apasionante', 'Festividad', ' Sol', 'Pantalón', 'Saltar', 'Barco', ' Cerámica', ' Interdependencia', ' Jugar', 'Elocuencia', 'Estimulado', 'Esencia', 'Salado', 'Confianza', 'Avena', ' Ética', 'Iniciativa', ' Platano', ' Nube', 'Exuberante', ' Escribir ', 'Encuentro', ' Nutrición', 'Deseo', ' Noble', ' Espiritualidad', ' Cooperación', ' Armonía', 'Pimienta', ' Superación', ' Sublime', 'Deslumbrante', 'Tradición', 'Flexibilidad', ' Universo', 'Jirafa', 'Calle', 'Diversidad', ' Actuar', ' Sensible', 'Técnico', 'Compasión', 'Espectacular', ' Arroz', ' Ave', ' Cuaderno', 'Genuino', 'Silencio', ' Queso', ' Camiseta', ' Madrugada', 'Abundancia', 'Compañerismo', 'Desafiante', 'Astonante', 'Impresión', ' Instituto', 'Atardecer', 'Logro', ' Tablet', ' Tormenta', ' Emprendimiento', 'Trueno', 'Excentricidad', 'Aldea', 'Sentimientos', 'Electrizado', 'Fascinante', 'Gratitud', ' Canela', 'Victoria', ' Lealtad', ' Bicicleta', ' Maíz', ' Éxito', 'Emoción', 'Educación', 'Cascada', 'Libertad', ' Odontología', ' Integridad', 'Sofá', 'Investigación', 'Queso', 'Iluminación', 'Generosidad', ' Pasión', 'Tierra', ' Poesía', 'Sacrificio', 'Resiliencia', 'Maravillosamente', 'Enérgico', 'Ventana']



        def Palabra_Aleatoria(lista_palabras):
            palabra_aleatoria = random.choice(lista_palabras)
            return palabra_aleatoria

        def ocultar_palabra(palabra):
            oculta = "_" * len(palabra)
            return oculta

        def mostrar_palabra(palabra_oculta):
            print("Palabra:", " ".join(palabra_oculta))

        def adivinar_letra():
             return input("Adivina una letra: ")

        def Stickman(intentos):
            if intentos == 1:
                print("  -------")
                print("  |     |")
                print("  |     O")
                print("  |    /|\\")
                print("  |    / \\")
                print("  |")
                print("=====")

            elif intentos == 0:
                print("  -------")
                print("  |")
                print("  |")
                print("  |")
                print("  |")
                print("  |")
                print("=====")
            elif intentos == 2:
                print("  |")
                print("  |")
                print("  |")
                print("  |")
                print("  |")
                print("=====")

            elif intentos == 3:
                print("")
                print("")
                print("")
                print("")
                print("")
                print("")
                print("=====")

        def jugar_ahorcado():
            palabra = Palabra_Aleatoria(lista)
            palabra_oculta = ocultar_palabra(palabra)
            intentos_totales = 3
            intentos_restantes = intentos_totales


            while intentos_restantes > 0:
                mostrar_palabra(palabra_oculta)
                Stickman(intentos_restantes)
                letra = adivinar_letra()
                acierto = False
                nueva_palabra_oculta = ""

            for i in range(len(palabra)):
                    if palabra[i].lower() == letra.lower():
                        nueva_palabra_oculta += letra
                        acierto = True
                    else:
                        nueva_palabra_oculta += palabra_oculta[i]

                    if acierto:
                        palabra_oculta = nueva_palabra_oculta
                        print("¡Correcto!")

                    else:
                        intentos_restantes -= 1
                        print("Incorrecto. Te quedan", intentos_restantes, "intentos.")

                    if palabra_oculta.lower() == palabra.lower():
                        print("¡Ganaste! Has adivinado la palabra:", palabra)
                        break

                    if intentos_restantes == 0:
                        print("¡Perdiste! La palabra era:", palabra)



        jugar_ahorcado()

elif a == 2:
    b=input("Por favor seleccione una dificultad:\n1.facil\n2.medio\n3.dificil" )
    if b == 1:

        lista = ['Companionship', 'Cookie', 'Hug', 'Loyalty', 'Enriching', 'Autumn', 'Ambition', 'Brilliant', 'Quietus', 'Science', 'Red', 'Pencil', 'Cinnamon', 'Air', 'Love', 'Highway', 'Patience', 'Solitude', 'Strategy', 'Progress', 'Fashion', 'Growth', 'Tenacity', 'Excited', 'Literature', 'Party', 'Hope', 'Inspiring', 'Innovation', 'Creativity', 'Electrifying', 'Enchantment', 'Meat', 'Watch', 'Silence', 'Course', 'Snow', 'Reverence', 'Ability', 'Dream', 'Orange', 'Marvel', 'Cordiality', 'Change', 'Computer', 'Music', 'Grape', 'Epiphany', 'Running', 'Gratitude', 'Leadership', 'Mystery', 'Glasses', 'Communication', 'Revelation', 'Acclaimed', 'Tears', 'Innovative', 'Whisper', 'Snow', 'Horizon', 'Marker', 'Discovery', 'Style', 'Enchanting', 'Sports', 'Literature', 'Healing', 'Serenity', 'Canine', 'Refreshing', 'Wonder', 'Office', 'Relaxation', 'Style', 'Vitality', 'Conservation', 'Dignity', 'Redemption', 'Swimming', 'Rest', 'Exciting', 'Profession', 'Oatmeal', 'Achievement', 'Applauded', 'Time', 'Yogurt', 'Ocean', 'Cinema', 'Village', 'Satisfaction', 'Coffee', 'Guitar', 'Water', 'Chalk', 'Responsibility', 'Prestige', 'Pleasure', 'Crying', 'Optimism', 'Team', 'Equality', 'Vanilla', 'Dance', 'Bus', 'Hobby', 'Imagination', 'Irresistible', 'Glow', 'Adaptability', 'Appreciation', 'Pen', 'Volunteering', 'Hope', 'Intriguing', 'Illuminating', 'Uplifting', 'Impressionism', 'Tuesday', 'Architecture', 'Progress', 'Stars', 'Community', 'Transcendental', 'Splendid', 'Hill', 'Environment', 'Soft drink', 'Dusk', 'Innocence', 'Corn', 'Courage', 'Surprised', 'Exercise', 'Wait', 'Photography', 'Reality', 'Nice', 'Enchantment', 'Dusk', 'Desert', 'Impressed', 'Sad', 'Oil', 'Euphoria', 'Painting', 'Well-being', 'Village', 'Glow', 'Reflection', 'Dance', 'Feather', 'Dedication', 'Delight', 'Laughter', 'Infatuation', 'Cake', 'Sports', 'Reinvention', 'Cocoa', 'Gastronomy', 'Symmetry', 'Fraternity', 'Engineer', 'Satisfactory', 'Cocoa', 'Aspiration', 'Authenticity', 'Humility', 'Intrigue', 'Pleasure', 'Consciousness', 'Exhilarating', 'Lawyer', 'Money', 'Yogurt', 'Unity', 'Computer', 'Juice', 'Fire', 'Recoil', 'Fascination', 'Planet', 'Happiness', 'Cat', 'Greatness', 'Elephant', 'Sweet', 'Rabbit', 'Plain', 'Bitter', 'Water', 'Book', 'Winter', 'Work',"Attraction", "Optimism", "Sculpture", "Gastronomy", "Beautiful", "Glasses", "Football", "Prodigy", "Experience", "Inspire", "Sea", "Mystical", "Nature", "Writing", "Fantasy", "Walking", "Joy", "Universe", "Tea", "Expression", "Laughter", "Spirituality", "Rejuvenation", "River", "Happiness", "Banana", "Yoga", "Emotional", "Opportunity", "House", "Pencil", "Patience", "Road", "Delight", "Trust", "Attraction", "Dream", "Impressive", "Birthday", "Nightmare", "Awe", "Clouds", "Wonderful", "Balance", "Collaboration", "Space", "Empowerment", "Design", "Studio", "Emotionally", "Resilience", "Basketball", "Radiant", "Empathy", "Interiors", "Astonishment", "Unforgettable", "Admiration", "Beautiful", "Mountain", "Fulfillment", "Acid", "Writing", "Hug", "Ceramics", "Jump", "Action", "Sigh", "Anger", "Table", "Hat", "Motorcycle", "Beer", "Shoes", "Truth", "Passionately", "Star", "Vacation", "Rhythm", "Sky", "Hobby", "Colorful", "Travel", "Dew", "Prodigious", "Psychology", "Sunrise", "Gratitude", "Challenge", "Swim", "Analysis", "Exquisite", "Heritage", "Television", "Pants", "Gift", "Reward", "Desert", "Nobility", "Connection", "Story", "School", "Maturity", "Rain", "Lamp", "Spontaneity", "Clear", "Constellation", "Mouse", "Culture", "Cool", "Inspiration", "Sun", "Guitar", "Book", "Diversity", "Risk", "Orange", "University", "Determination", "Festival", "Kindness", "Breeze", "Hamster", "Highway", "Marvel", "Bee", "Hope", "Knowledge", "Hill", "Hamster", "Kind", "Energy", "Radiant", "Medicine", "Swimming", "Waterfall", "Affectionate", "Warm", "Friendship", "Telephone", "Rabbit", "Monday", "Outdoors", "Road", "Bright", "Saxophone", "Ethics", "Tennis", "Truck", "Learning", "Sincerity", "Sustainability", "Kindness", "Jungle", "Radiance", "Focus", "Dog", "University", "Upbringing", "Discovery", "Garden", "Skill", "Train", "Lighting", "Planning", "Sand", "Tennis", "Lush", "Overcoming", "Summer", "Engineer", "Forest", "Storm", "Transcendence", "Divorced", "Harmony", "Empathy", "Respect", "Clock", "Friend", "Thread", "Yogurt", "School", "Serendipity", "Plane", "Game", "Laughter", "Fulfillment", "Hospital", "Smile", "Captivating", "Intuition", "Experience", "Splendor", "Ocean", "Prosperity", "Consciousness", "Tequila", "Anniversary", "Seduction", "Leadership", "Outstanding", "Courte",'Renewal', 'Valley', 'Morning', 'Night', 'Winter', 'Charisma', 'Evolution', 'Flexibility', 'Energetic', 'Change', 'Basketball', 'Professionalism', 'Inspiration', 'Exciting', 'Wonderful', 'Success', 'Solidarity', 'Renaissance', 'Vegetable', 'Dress', 'Shells', 'Sea', 'Doctor', 'Faith', 'T-shirt', 'Creativity', 'Bitter', 'Celebration', 'Vitality', 'Flowers', 'Night', 'Cheerful', 'Gratification', 'Adventure', 'Pepper', 'Spring', 'Stimulating', 'Roof', 'Sugar', 'Dress', 'Calm', 'Freedom', 'Tranquility', 'Awareness', 'Anniversary', 'Moments', 'Happy', 'Galaxy', 'Authenticity', 'Meditation', 'Competition', 'Tree', 'Nutrition', 'Glorious', 'Science', 'Elevation', 'Air', 'Justice', 'Efficiency', 'Charm', 'Fire', 'Tradition', 'Oasis', 'Surprise', 'Teaching', 'Joy', 'Dreaming', 'Overflowing', 'Adventure', 'Television', 'Shoes', 'Chocolate', 'Dog', 'Inspiration', 'Wedding', 'Anger', 'Passionate', 'Medicine', 'Brush', 'Clarity', 'Immersive', 'Pizza', 'Moon', 'Justice', 'Empowerment', 'Chair', 'Overwhelmed', 'Wind', 'Wealth', 'Memories', 'Enthusiasm', 'Technology', 'Store', 'Galaxy', 'Magic', 'Charming', 'Pasta', 'Exuberance', 'Equity', 'Cinema', 'Perseverance', 'Organization', 'Perseverance', 'Career', 'Astounded', 'Dreams', 'Originality', 'Extraordinary', 'Transcendental', 'Office', 'Plain', 'Milk', 'Skateboard', 'Cellphone', 'Intelligence', 'Relaxing', 'Sound', 'Rapture', 'Sunset', 'Inspiring', 'Walking', 'Serenity', 'Fantasy', 'Emancipating', 'Attentive', 'Ice cream', 'Afternoon', 'Pencil', 'Belonging', 'Entrepreneurship', 'Integrity', 'Innocence', 'Harmony', 'Self-esteem', 'Joy', 'Tea', 'Notebook', 'Painting', 'Rice', 'Enrichment', 'Motivating', 'Inclusion', 'Apple', 'Mindfulness', 'Respect', 'Exploration', 'Neighbor', 'Wealth', 'Transformation', 'Painting', 'Joy', 'Chaos', 'Earth', 'Butterfly', 'Admiration', 'Exotic', 'Sustainability', 'Passionate', 'Vanilla', 'Fascinating', 'Acid', 'Tiger', 'Sadness', 'Vision', 'Lightning', 'Satellite', 'Sincere', 'Cellphone', 'Vegetable', 'Revitalizing', 'Whisky', 'Theater', 'Landscape', 'Sensation', 'Strength', 'Street', 'Door', 'Meat', 'Mystery', 'Theater', 'Pasta', 'Saturday', 'Commitment', 'Triumph', 'Fascinating', 'Courage', 'Wheat', 'Thunder', 'Childhood', 'Dream', 'Excitement', 'Health', 'Honesty', 'Art', 'Disruption', 'Dance', 'Endurance', 'Song', 'Kindness', 'Wine', 'Hope', 'Sweet', 'Bravery', 'Elegance', 'Melody', 'Passion', 'Sunrise', 'Laughter', 'Emotion', 'Beauty', 'Heart', 'Quiet', 'Journey', 'Friendship', 'Knowledge', 'Embrace', 'Time', 'Energy', 'Love', 'Rain', 'Confidence', 'Smile', 'Inspiration', 'Family', 'Freedom', 'Peace', 'Happiness',"window" ]



        def Palabra_Aleatoria(lista_palabras):
            palabra_aleatoria = random.choice(lista_palabras)
            return palabra_aleatoria

        def ocultar_palabra(palabra):
            oculta = "_" * len(palabra)
            return oculta

        def mostrar_palabra(palabra_oculta):
            print("Palabra:", " ".join(palabra_oculta))

        def adivinar_letra():
            return input("Adivina una letra: ")

        def Stickman(intentos):
            if intentos == range(1, 1000):
                print("")
                print("")
                print("")
                print("")
                print("")
                print("")
                print("=====")

        def jugar_ahorcado():
            palabra = Palabra_Aleatoria(lista)
            palabra_oculta = ocultar_palabra(palabra)
            intentos_totales = 1000
            intentos_restantes = intentos_totales


            while intentos_restantes > 0:
                mostrar_palabra(palabra_oculta)
                Stickman(intentos_restantes)
                letra = adivinar_letra()
                acierto = False
                nueva_palabra_oculta = ""

                for i in range(len(palabra)):
                    if palabra[i].lower() == letra.lower():
                        nueva_palabra_oculta += letra
                        acierto = True
                    else:
                        nueva_palabra_oculta += palabra_oculta[i]

                if acierto:
                    palabra_oculta = nueva_palabra_oculta
                    print("¡Correcto!")

                else:
                    intentos_restantes -= 1
                    print("Incorrecto. Te quedan", intentos_restantes, "intentos.")

                if palabra_oculta.lower() == palabra.lower():
                    print("¡Ganaste! Has adivinado la palabra:", palabra)
                    break

            if intentos_restantes == 0:
                    print("¡Perdiste! La palabra era:", palabra)



        jugar_ahorcado()
        
    elif b == 2:
        import random

        lista = ['Companionship', 'Cookie', 'Hug', 'Loyalty', 'Enriching', 'Autumn', 'Ambition', 'Brilliant', 'Quietus', 'Science', 'Red', 'Pencil', 'Cinnamon', 'Air', 'Love', 'Highway', 'Patience', 'Solitude', 'Strategy', 'Progress', 'Fashion', 'Growth', 'Tenacity', 'Excited', 'Literature', 'Party', 'Hope', 'Inspiring', 'Innovation', 'Creativity', 'Electrifying', 'Enchantment', 'Meat', 'Watch', 'Silence', 'Course', 'Snow', 'Reverence', 'Ability', 'Dream', 'Orange', 'Marvel', 'Cordiality', 'Change', 'Computer', 'Music', 'Grape', 'Epiphany', 'Running', 'Gratitude', 'Leadership', 'Mystery', 'Glasses', 'Communication', 'Revelation', 'Acclaimed', 'Tears', 'Innovative', 'Whisper', 'Snow', 'Horizon', 'Marker', 'Discovery', 'Style', 'Enchanting', 'Sports', 'Literature', 'Healing', 'Serenity', 'Canine', 'Refreshing', 'Wonder', 'Office', 'Relaxation', 'Style', 'Vitality', 'Conservation', 'Dignity', 'Redemption', 'Swimming', 'Rest', 'Exciting', 'Profession', 'Oatmeal', 'Achievement', 'Applauded', 'Time', 'Yogurt', 'Ocean', 'Cinema', 'Village', 'Satisfaction', 'Coffee', 'Guitar', 'Water', 'Chalk', 'Responsibility', 'Prestige', 'Pleasure', 'Crying', 'Optimism', 'Team', 'Equality', 'Vanilla', 'Dance', 'Bus', 'Hobby', 'Imagination', 'Irresistible', 'Glow', 'Adaptability', 'Appreciation', 'Pen', 'Volunteering', 'Hope', 'Intriguing', 'Illuminating', 'Uplifting', 'Impressionism', 'Tuesday', 'Architecture', 'Progress', 'Stars', 'Community', 'Transcendental', 'Splendid', 'Hill', 'Environment', 'Soft drink', 'Dusk', 'Innocence', 'Corn', 'Courage', 'Surprised', 'Exercise', 'Wait', 'Photography', 'Reality', 'Nice', 'Enchantment', 'Dusk', 'Desert', 'Impressed', 'Sad', 'Oil', 'Euphoria', 'Painting', 'Well-being', 'Village', 'Glow', 'Reflection', 'Dance', 'Feather', 'Dedication', 'Delight', 'Laughter', 'Infatuation', 'Cake', 'Sports', 'Reinvention', 'Cocoa', 'Gastronomy', 'Symmetry', 'Fraternity', 'Engineer', 'Satisfactory', 'Cocoa', 'Aspiration', 'Authenticity', 'Humility', 'Intrigue', 'Pleasure', 'Consciousness', 'Exhilarating', 'Lawyer', 'Money', 'Yogurt', 'Unity', 'Computer', 'Juice', 'Fire', 'Recoil', 'Fascination', 'Planet', 'Happiness', 'Cat', 'Greatness', 'Elephant', 'Sweet', 'Rabbit', 'Plain', 'Bitter', 'Water', 'Book', 'Winter', 'Work',"Attraction", "Optimism", "Sculpture", "Gastronomy", "Beautiful", "Glasses", "Football", "Prodigy", "Experience", "Inspire", "Sea", "Mystical", "Nature", "Writing", "Fantasy", "Walking", "Joy", "Universe", "Tea", "Expression", "Laughter", "Spirituality", "Rejuvenation", "River", "Happiness", "Banana", "Yoga", "Emotional", "Opportunity", "House", "Pencil", "Patience", "Road", "Delight", "Trust", "Attraction", "Dream", "Impressive", "Birthday", "Nightmare", "Awe", "Clouds", "Wonderful", "Balance", "Collaboration", "Space", "Empowerment", "Design", "Studio", "Emotionally", "Resilience", "Basketball", "Radiant", "Empathy", "Interiors", "Astonishment", "Unforgettable", "Admiration", "Beautiful", "Mountain", "Fulfillment", "Acid", "Writing", "Hug", "Ceramics", "Jump", "Action", "Sigh", "Anger", "Table", "Hat", "Motorcycle", "Beer", "Shoes", "Truth", "Passionately", "Star", "Vacation", "Rhythm", "Sky", "Hobby", "Colorful", "Travel", "Dew", "Prodigious", "Psychology", "Sunrise", "Gratitude", "Challenge", "Swim", "Analysis", "Exquisite", "Heritage", "Television", "Pants", "Gift", "Reward", "Desert", "Nobility", "Connection", "Story", "School", "Maturity", "Rain", "Lamp", "Spontaneity", "Clear", "Constellation", "Mouse", "Culture", "Cool", "Inspiration", "Sun", "Guitar", "Book", "Diversity", "Risk", "Orange", "University", "Determination", "Festival", "Kindness", "Breeze", "Hamster", "Highway", "Marvel", "Bee", "Hope", "Knowledge", "Hill", "Hamster", "Kind", "Energy", "Radiant", "Medicine", "Swimming", "Waterfall", "Affectionate", "Warm", "Friendship", "Telephone", "Rabbit", "Monday", "Outdoors", "Road", "Bright", "Saxophone", "Ethics", "Tennis", "Truck", "Learning", "Sincerity", "Sustainability", "Kindness", "Jungle", "Radiance", "Focus", "Dog", "University", "Upbringing", "Discovery", "Garden", "Skill", "Train", "Lighting", "Planning", "Sand", "Tennis", "Lush", "Overcoming", "Summer", "Engineer", "Forest", "Storm", "Transcendence", "Divorced", "Harmony", "Empathy", "Respect", "Clock", "Friend", "Thread", "Yogurt", "School", "Serendipity", "Plane", "Game", "Laughter", "Fulfillment", "Hospital", "Smile", "Captivating", "Intuition", "Experience", "Splendor", "Ocean", "Prosperity", "Consciousness", "Tequila", "Anniversary", "Seduction", "Leadership", "Outstanding", "Courte",'Renewal', 'Valley', 'Morning', 'Night', 'Winter', 'Charisma', 'Evolution', 'Flexibility', 'Energetic', 'Change', 'Basketball', 'Professionalism', 'Inspiration', 'Exciting', 'Wonderful', 'Success', 'Solidarity', 'Renaissance', 'Vegetable', 'Dress', 'Shells', 'Sea', 'Doctor', 'Faith', 'T-shirt', 'Creativity', 'Bitter', 'Celebration', 'Vitality', 'Flowers', 'Night', 'Cheerful', 'Gratification', 'Adventure', 'Pepper', 'Spring', 'Stimulating', 'Roof', 'Sugar', 'Dress', 'Calm', 'Freedom', 'Tranquility', 'Awareness', 'Anniversary', 'Moments', 'Happy', 'Galaxy', 'Authenticity', 'Meditation', 'Competition', 'Tree', 'Nutrition', 'Glorious', 'Science', 'Elevation', 'Air', 'Justice', 'Efficiency', 'Charm', 'Fire', 'Tradition', 'Oasis', 'Surprise', 'Teaching', 'Joy', 'Dreaming', 'Overflowing', 'Adventure', 'Television', 'Shoes', 'Chocolate', 'Dog', 'Inspiration', 'Wedding', 'Anger', 'Passionate', 'Medicine', 'Brush', 'Clarity', 'Immersive', 'Pizza', 'Moon', 'Justice', 'Empowerment', 'Chair', 'Overwhelmed', 'Wind', 'Wealth', 'Memories', 'Enthusiasm', 'Technology', 'Store', 'Galaxy', 'Magic', 'Charming', 'Pasta', 'Exuberance', 'Equity', 'Cinema', 'Perseverance', 'Organization', 'Perseverance', 'Career', 'Astounded', 'Dreams', 'Originality', 'Extraordinary', 'Transcendental', 'Office', 'Plain', 'Milk', 'Skateboard', 'Cellphone', 'Intelligence', 'Relaxing', 'Sound', 'Rapture', 'Sunset', 'Inspiring', 'Walking', 'Serenity', 'Fantasy', 'Emancipating', 'Attentive', 'Ice cream', 'Afternoon', 'Pencil', 'Belonging', 'Entrepreneurship', 'Integrity', 'Innocence', 'Harmony', 'Self-esteem', 'Joy', 'Tea', 'Notebook', 'Painting', 'Rice', 'Enrichment', 'Motivating', 'Inclusion', 'Apple', 'Mindfulness', 'Respect', 'Exploration', 'Neighbor', 'Wealth', 'Transformation', 'Painting', 'Joy', 'Chaos', 'Earth', 'Butterfly', 'Admiration', 'Exotic', 'Sustainability', 'Passionate', 'Vanilla', 'Fascinating', 'Acid', 'Tiger', 'Sadness', 'Vision', 'Lightning', 'Satellite', 'Sincere', 'Cellphone', 'Vegetable', 'Revitalizing', 'Whisky', 'Theater', 'Landscape', 'Sensation', 'Strength', 'Street', 'Door', 'Meat', 'Mystery', 'Theater', 'Pasta', 'Saturday', 'Commitment', 'Triumph', 'Fascinating', 'Courage', 'Wheat', 'Thunder', 'Childhood', 'Dream', 'Excitement', 'Health', 'Honesty', 'Art', 'Disruption', 'Dance', 'Endurance', 'Song', 'Kindness', 'Wine', 'Hope', 'Sweet', 'Bravery', 'Elegance', 'Melody', 'Passion', 'Sunrise', 'Laughter', 'Emotion', 'Beauty', 'Heart', 'Quiet', 'Journey', 'Friendship', 'Knowledge', 'Embrace', 'Time', 'Energy', 'Love', 'Rain', 'Confidence', 'Smile', 'Inspiration', 'Family', 'Freedom', 'Peace', 'Happiness',"window" ]
        def Palabra_Aleatoria(lista_palabras):
            palabra_aleatoria = random.choice(lista_palabras)
            return palabra_aleatoria

        def ocultar_palabra(palabra):
            oculta = "_" * len(palabra)
            return oculta

        def mostrar_palabra(palabra_oculta):
            print("Palabra:", " ".join(palabra_oculta))

        def adivinar_letra():
            return input("Adivina una letra: ")

        def Stickman(intentos):
            if intentos == 0:
                print("  -------")
                print("  |     |")
                print("  |     O")
                print("  |    /|\\")
                print("  |    / \\")
                print("  |")
                print("=====")
            elif intentos == 1:
                print("  -------")
                print("  |     |")
                print("  |     O")
                print("  |    /|\\")
                print("  |    /")
                print("  |")
                print("=====")
            elif intentos == 2:
                print("  -------")
                print("  |     |")
                print("  |     O")
                print("  |    /|\\")
                print("  |")
                print("  |")
                print("=====")
            elif intentos == 3:
                print("  -------")
                print("  |     |")
                print("  |     O")
                print("  |     |\\")
                print("  |")
                print("  |")
                print("=====")
            elif intentos == 4:
                print("  -------")
                print("  |     |")
                print("  |     O")
                print("  |     |")
                print("  |")
                print("  |")
                print("=====")
            elif intentos == 5:
                print("  -------")
                print("  |     |")
                print("  |     O")
                print("  |")
                print("  |")
                print("  |")
                print("=====")
            elif intentos == 6:
                print("  -------")
                print("  |     |")
                print("  |")
                print("  |")
                print("  |")
                print("  |")
                print("=====")
            elif intentos == 7:
                print("  -------")
                print("  |")
                print("  |")
                print("  |")
                print("  |")
                print("  |")
                print("=====")
            elif intentos == 8:
                print("  |")
                print("  |")
                print("  |")
                print("  |")
                print("  |")
                print("=====")
            elif intentos == 9:
                print("")
                print("")
                print("")
                print("")
                print("")
                print("")
                print("=====")
            elif intentos == 10:
                print("")
                print("")
                print("")
                print("")
                print("")
                print("")
                print("=====")

        def jugar_ahorcado():
            palabra = Palabra_Aleatoria(lista)
            palabra_oculta = ocultar_palabra(palabra)
            intentos_totales = 10
            intentos_restantes = intentos_totales


            while intentos_restantes > 0:
                mostrar_palabra(palabra_oculta)
                Stickman(intentos_restantes)
                letra = adivinar_letra()
                acierto = False
                nueva_palabra_oculta = ""

                for i in range(len(palabra)):
                    if palabra[i].lower() == letra.lower():
                        nueva_palabra_oculta += letra
                        acierto = True
                    else:
                        nueva_palabra_oculta += palabra_oculta[i]

                if acierto:
                    palabra_oculta = nueva_palabra_oculta
                    print("¡Correcto!")

                else:
                    intentos_restantes -= 1
                    print("Incorrecto. Te quedan", intentos_restantes, "intentos.")

                if palabra_oculta.lower() == palabra.lower():
                    print("¡Ganaste! Has adivinado la palabra:", palabra)
                    break

                if intentos_restantes == 0:
                    print("¡Perdiste! La palabra era:", palabra)



        jugar_ahorcado()


    elif b == 3:
        lista = ['Companionship', 'Cookie', 'Hug', 'Loyalty', 'Enriching', 'Autumn', 'Ambition', 'Brilliant', 'Quietus', 'Science', 'Red', 'Pencil', 'Cinnamon', 'Air', 'Love', 'Highway', 'Patience', 'Solitude', 'Strategy', 'Progress', 'Fashion', 'Growth', 'Tenacity', 'Excited', 'Literature', 'Party', 'Hope', 'Inspiring', 'Innovation', 'Creativity', 'Electrifying', 'Enchantment', 'Meat', 'Watch', 'Silence', 'Course', 'Snow', 'Reverence', 'Ability', 'Dream', 'Orange', 'Marvel', 'Cordiality', 'Change', 'Computer', 'Music', 'Grape', 'Epiphany', 'Running', 'Gratitude', 'Leadership', 'Mystery', 'Glasses', 'Communication', 'Revelation', 'Acclaimed', 'Tears', 'Innovative', 'Whisper', 'Snow', 'Horizon', 'Marker', 'Discovery', 'Style', 'Enchanting', 'Sports', 'Literature', 'Healing', 'Serenity', 'Canine', 'Refreshing', 'Wonder', 'Office', 'Relaxation', 'Style', 'Vitality', 'Conservation', 'Dignity', 'Redemption', 'Swimming', 'Rest', 'Exciting', 'Profession', 'Oatmeal', 'Achievement', 'Applauded', 'Time', 'Yogurt', 'Ocean', 'Cinema', 'Village', 'Satisfaction', 'Coffee', 'Guitar', 'Water', 'Chalk', 'Responsibility', 'Prestige', 'Pleasure', 'Crying', 'Optimism', 'Team', 'Equality', 'Vanilla', 'Dance', 'Bus', 'Hobby', 'Imagination', 'Irresistible', 'Glow', 'Adaptability', 'Appreciation', 'Pen', 'Volunteering', 'Hope', 'Intriguing', 'Illuminating', 'Uplifting', 'Impressionism', 'Tuesday', 'Architecture', 'Progress', 'Stars', 'Community', 'Transcendental', 'Splendid', 'Hill', 'Environment', 'Soft drink', 'Dusk', 'Innocence', 'Corn', 'Courage', 'Surprised', 'Exercise', 'Wait', 'Photography', 'Reality', 'Nice', 'Enchantment', 'Dusk', 'Desert', 'Impressed', 'Sad', 'Oil', 'Euphoria', 'Painting', 'Well-being', 'Village', 'Glow', 'Reflection', 'Dance', 'Feather', 'Dedication', 'Delight', 'Laughter', 'Infatuation', 'Cake', 'Sports', 'Reinvention', 'Cocoa', 'Gastronomy', 'Symmetry', 'Fraternity', 'Engineer', 'Satisfactory', 'Cocoa', 'Aspiration', 'Authenticity', 'Humility', 'Intrigue', 'Pleasure', 'Consciousness', 'Exhilarating', 'Lawyer', 'Money', 'Yogurt', 'Unity', 'Computer', 'Juice', 'Fire', 'Recoil', 'Fascination', 'Planet', 'Happiness', 'Cat', 'Greatness', 'Elephant', 'Sweet', 'Rabbit', 'Plain', 'Bitter', 'Water', 'Book', 'Winter', 'Work',"Attraction", "Optimism", "Sculpture", "Gastronomy", "Beautiful", "Glasses", "Football", "Prodigy", "Experience", "Inspire", "Sea", "Mystical", "Nature", "Writing", "Fantasy", "Walking", "Joy", "Universe", "Tea", "Expression", "Laughter", "Spirituality", "Rejuvenation", "River", "Happiness", "Banana", "Yoga", "Emotional", "Opportunity", "House", "Pencil", "Patience", "Road", "Delight", "Trust", "Attraction", "Dream", "Impressive", "Birthday", "Nightmare", "Awe", "Clouds", "Wonderful", "Balance", "Collaboration", "Space", "Empowerment", "Design", "Studio", "Emotionally", "Resilience", "Basketball", "Radiant", "Empathy", "Interiors", "Astonishment", "Unforgettable", "Admiration", "Beautiful", "Mountain", "Fulfillment", "Acid", "Writing", "Hug", "Ceramics", "Jump", "Action", "Sigh", "Anger", "Table", "Hat", "Motorcycle", "Beer", "Shoes", "Truth", "Passionately", "Star", "Vacation", "Rhythm", "Sky", "Hobby", "Colorful", "Travel", "Dew", "Prodigious", "Psychology", "Sunrise", "Gratitude", "Challenge", "Swim", "Analysis", "Exquisite", "Heritage", "Television", "Pants", "Gift", "Reward", "Desert", "Nobility", "Connection", "Story", "School", "Maturity", "Rain", "Lamp", "Spontaneity", "Clear", "Constellation", "Mouse", "Culture", "Cool", "Inspiration", "Sun", "Guitar", "Book", "Diversity", "Risk", "Orange", "University", "Determination", "Festival", "Kindness", "Breeze", "Hamster", "Highway", "Marvel", "Bee", "Hope", "Knowledge", "Hill", "Hamster", "Kind", "Energy", "Radiant", "Medicine", "Swimming", "Waterfall", "Affectionate", "Warm", "Friendship", "Telephone", "Rabbit", "Monday", "Outdoors", "Road", "Bright", "Saxophone", "Ethics", "Tennis", "Truck", "Learning", "Sincerity", "Sustainability", "Kindness", "Jungle", "Radiance", "Focus", "Dog", "University", "Upbringing", "Discovery", "Garden", "Skill", "Train", "Lighting", "Planning", "Sand", "Tennis", "Lush", "Overcoming", "Summer", "Engineer", "Forest", "Storm", "Transcendence", "Divorced", "Harmony", "Empathy", "Respect", "Clock", "Friend", "Thread", "Yogurt", "School", "Serendipity", "Plane", "Game", "Laughter", "Fulfillment", "Hospital", "Smile", "Captivating", "Intuition", "Experience", "Splendor", "Ocean", "Prosperity", "Consciousness", "Tequila", "Anniversary", "Seduction", "Leadership", "Outstanding", "Courte",'Renewal', 'Valley', 'Morning', 'Night', 'Winter', 'Charisma', 'Evolution', 'Flexibility', 'Energetic', 'Change', 'Basketball', 'Professionalism', 'Inspiration', 'Exciting', 'Wonderful', 'Success', 'Solidarity', 'Renaissance', 'Vegetable', 'Dress', 'Shells', 'Sea', 'Doctor', 'Faith', 'T-shirt', 'Creativity', 'Bitter', 'Celebration', 'Vitality', 'Flowers', 'Night', 'Cheerful', 'Gratification', 'Adventure', 'Pepper', 'Spring', 'Stimulating', 'Roof', 'Sugar', 'Dress', 'Calm', 'Freedom', 'Tranquility', 'Awareness', 'Anniversary', 'Moments', 'Happy', 'Galaxy', 'Authenticity', 'Meditation', 'Competition', 'Tree', 'Nutrition', 'Glorious', 'Science', 'Elevation', 'Air', 'Justice', 'Efficiency', 'Charm', 'Fire', 'Tradition', 'Oasis', 'Surprise', 'Teaching', 'Joy', 'Dreaming', 'Overflowing', 'Adventure', 'Television', 'Shoes', 'Chocolate', 'Dog', 'Inspiration', 'Wedding', 'Anger', 'Passionate', 'Medicine', 'Brush', 'Clarity', 'Immersive', 'Pizza', 'Moon', 'Justice', 'Empowerment', 'Chair', 'Overwhelmed', 'Wind', 'Wealth', 'Memories', 'Enthusiasm', 'Technology', 'Store', 'Galaxy', 'Magic', 'Charming', 'Pasta', 'Exuberance', 'Equity', 'Cinema', 'Perseverance', 'Organization', 'Perseverance', 'Career', 'Astounded', 'Dreams', 'Originality', 'Extraordinary', 'Transcendental', 'Office', 'Plain', 'Milk', 'Skateboard', 'Cellphone', 'Intelligence', 'Relaxing', 'Sound', 'Rapture', 'Sunset', 'Inspiring', 'Walking', 'Serenity', 'Fantasy', 'Emancipating', 'Attentive', 'Ice cream', 'Afternoon', 'Pencil', 'Belonging', 'Entrepreneurship', 'Integrity', 'Innocence', 'Harmony', 'Self-esteem', 'Joy', 'Tea', 'Notebook', 'Painting', 'Rice', 'Enrichment', 'Motivating', 'Inclusion', 'Apple', 'Mindfulness', 'Respect', 'Exploration', 'Neighbor', 'Wealth', 'Transformation', 'Painting', 'Joy', 'Chaos', 'Earth', 'Butterfly', 'Admiration', 'Exotic', 'Sustainability', 'Passionate', 'Vanilla', 'Fascinating', 'Acid', 'Tiger', 'Sadness', 'Vision', 'Lightning', 'Satellite', 'Sincere', 'Cellphone', 'Vegetable', 'Revitalizing', 'Whisky', 'Theater', 'Landscape', 'Sensation', 'Strength', 'Street', 'Door', 'Meat', 'Mystery', 'Theater', 'Pasta', 'Saturday', 'Commitment', 'Triumph', 'Fascinating', 'Courage', 'Wheat', 'Thunder', 'Childhood', 'Dream', 'Excitement', 'Health', 'Honesty', 'Art', 'Disruption', 'Dance', 'Endurance', 'Song', 'Kindness', 'Wine', 'Hope', 'Sweet', 'Bravery', 'Elegance', 'Melody', 'Passion', 'Sunrise', 'Laughter', 'Emotion', 'Beauty', 'Heart', 'Quiet', 'Journey', 'Friendship', 'Knowledge', 'Embrace', 'Time', 'Energy', 'Love', 'Rain', 'Confidence', 'Smile', 'Inspiration', 'Family', 'Freedom', 'Peace', 'Happiness',"Window" ]



        def Palabra_Aleatoria(lista_palabras):
            palabra_aleatoria = random.choice(lista_palabras)
            return palabra_aleatoria

        def ocultar_palabra(palabra):
            oculta = "_" * len(palabra)
            return oculta

        def mostrar_palabra(palabra_oculta):
            print("Palabra:", " ".join(palabra_oculta))

        def adivinar_letra():
             return input("Adivina una letra: ")

        def Stickman(intentos):
            if intentos == 1:
                print("  -------")
                print("  |     |")
                print("  |     O")
                print("  |    /|\\")
                print("  |    / \\")
                print("  |")
                print("=====")

            elif intentos == 0:
                print("  -------")
                print("  |")
                print("  |")
                print("  |")
                print("  |")
                print("  |")
                print("=====")
            elif intentos == 2:
                print("  |")
                print("  |")
                print("  |")
                print("  |")
                print("  |")
                print("=====")

            elif intentos == 3:
                print("")
                print("")
                print("")
                print("")
                print("")
                print("")
                print("=====")

        def jugar_ahorcado():
            palabra = Palabra_Aleatoria(lista)
            palabra_oculta = ocultar_palabra(palabra)
            intentos_totales = 3
            intentos_restantes = intentos_totales


            while intentos_restantes > 0:
                mostrar_palabra(palabra_oculta)
                Stickman(intentos_restantes)
                letra = adivinar_letra()
                acierto = False
                nueva_palabra_oculta = ""

            for i in range(len(palabra)):
                    if palabra[i].lower() == letra.lower():
                        nueva_palabra_oculta += letra
                        acierto = True
                    else:
                        nueva_palabra_oculta += palabra_oculta[i]

                    if acierto:
                        palabra_oculta = nueva_palabra_oculta
                        print("¡Correcto!")

                    else:
                        intentos_restantes -= 1
                        print("Incorrecto. Te quedan", intentos_restantes, "intentos.")

                    if palabra_oculta.lower() == palabra.lower():
                        print("¡Ganaste! Has adivinado la palabra:", palabra)
                        break

                    if intentos_restantes == 0:
                        print("¡Perdiste! La palabra era:", palabra)



        jugar_ahorcado()
```
