<!DOCTYPE html>

<html lang="en">
<head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>Simulador Cardio Respiratorio</title>
<style>
        body {
            font-family: Arial, sans-serif;
        }

        #simulator {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 500px;
        }

        #heart, #lungs {
            width: 150px;
            animation-play-state: running;
        }

        @keyframes heartbeat {
            0% {
                transform: scale(1);
            }
            50% {
                transform: scale(1.1);
            }
            100% {
                transform: scale(1);
            }
        }

        @keyframes breathing {
            0% {
                transform: scale(1);
            }
            50% {
                transform: scale(1.05);
            }
            100% {
                transform: scale(1);
            }
        }

        #controls {
            display: flex;
            flex-direction: column;
            gap: 15px;
            margin-top: 20px;
        }
    </style>
</head>
<audio id="heartbeatAudio" loop="">
<source src="/mnt/data/salamisound-8309447-heartbeat-pulse-normal.mp3" type="audio/mpeg"/>
    Your browser does not support the audio element.
</audio>
<body style="background-color: green;"><div style="position: absolute; top: 10px; right: 10px; font-size: 0.8em; opacity: 0.7;">Prof. Nicolás Leites</div>
<h1>Simulador Cardio Respiratorio</h1>
<div id="simulator">
<img alt="Corazón" id="heart" src="https://www.aboutespanol.com/thmb/Qu2ky_WqHgfjcO6hLPZrRTgGgAg=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc()/comofuncionaelcorazon-56cb62563df78cfb379ca9c8.jpg" style="animation: heartbeat 1s infinite;"/>
<img alt="Pulmones" id="lungs" src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/9e/Lungs_diagram_simple.svg/1200px-Lungs_diagram_simple.svg.png" style="animation: breathing 2s infinite;"/>
</div>
<button id="resetButton" style="border-radius: 50%; padding: 10px 20px; margin: 20px 0;">Volver a valores normales</button>
<label>Presión Sanguínea: 
    <input id="bloodPressure" max="180" min="80" type="range" value="120"/>
<span id="bloodPressureValue">120</span> mmHg
</label>
<button id="toggleAudioButton" onclick="toggleAudio()" style="margin: 20px 0;">Iniciar/Detener Audio de Latidos</button>
<script>
    function toggleAudio() {
        const heartbeatAudio = document.getElementById('heartbeatAudio');
        if (heartbeatAudio.paused) {
            heartbeatAudio.play();
        } else {
            heartbeatAudio.pause();
        }
    }
</script>
<div id="controls">
<label>Frecuencia Cardíaca: <input id="heartRate" max="200" min="30" type="range" value="75"/> &lt;span id='heartRateValue'&gt;75&lt;/span&gt; latidos/minuto</label>
<label>Frecuencia Respiratoria: <input id="breathingRate" max="40" min="5" type="range" value="15"/> &lt;span id='breathingRateValue'&gt;15&lt;/span&gt; respiraciones/minuto</label>
<button onclick="simulate('asma')">Asma</button>
<button onclick="simulate('infarto')">Infarto de Miocardio</button>
<button onclick="simulate('hipoxia')">Hipoxia</button>
<button onclick="simulate('hiperventilacion')">Hiperventilación</button>
<!-- Agrega más botones según necesites -->
</div>
<script>
    function simulate(condition) {
        const heartRateSlider = document.getElementById('heartRate');
        const breathingRateSlider = document.getElementById('breathingRate');
        const bloodPressureSlider = document.getElementById('bloodPressure');

        const heartRateValue = document.getElementById('heartRateValue');
        const breathingRateValue = document.getElementById('breathingRateValue');
        const bloodPressureValue = document.getElementById('bloodPressureValue');

        switch(condition) {
            case 'asma':
                heartRateSlider.value = 110;
                breathingRateSlider.value = 40; // Adjusted value
                bloodPressureSlider.value = 130;
                break;
            case 'infarto':
                heartRateSlider.value = 130;
                breathingRateSlider.value = 28; // Adjusted value
                bloodPressureSlider.value = 100;
                break;
            case 'hipoxia':
                heartRateSlider.value = 120;
                breathingRateSlider.value = 45; // Adjusted value
                bloodPressureSlider.value = 110;
                break;
            case 'hiperventilacion':
                heartRateSlider.value = 105;
                breathingRateSlider.value = 50; // Adjusted value
                bloodPressureSlider.value = 125;
                break;
            default:
                break;
        }

        heartRateValue.innerText = heartRateSlider.value;
        breathingRateValue.innerText = breathingRateSlider.value;
        bloodPressureValue.innerText = bloodPressureSlider.value;
    }
</script>
<script>
    const heartRateSlider = document.getElementById('heartRate');
    const breathingRateSlider = document.getElementById('breathingRate');
    const heartRateValue = document.getElementById('heartRateValue');
    const breathingRateValue = document.getElementById('breathingRateValue');

    heartRateSlider.addEventListener('input', function() {
        heartRateValue.innerText = heartRateSlider.value;
        breathingRateSlider.value = Math.round(heartRateSlider.value / 4);
        breathingRateValue.innerText = breathingRateSlider.value;
    });

    breathingRateSlider.addEventListener('input', function() {
        breathingRateValue.innerText = breathingRateSlider.value;
        heartRateSlider.value = breathingRateSlider.value * 4;
        heartRateValue.innerText = heartRateSlider.value;
    });
</script>
<script>
    const heart = document.getElementById('heart');
    const lungs = document.getElementById('lungs');
    const heartRateControl = document.getElementById('heartRate');
    const breathingRateControl = document.getElementById('breathingRate');

    heartRateControl.addEventListener('input', function() {
        const bpm = this.value;
        heart.style.animationDuration = `${60 / bpm}s`;
    });

    breathingRateControl.addEventListener('input', function() {
        const rpm = this.value;
        lungs.style.animationDuration = `${60 / rpm}s`;
    });
</script>
<script>
    function simulate(condition) {
        const heartRateSlider = document.getElementById('heartRate');
        const breathingRateSlider = document.getElementById('breathingRate');
        const bloodPressureSlider = document.getElementById('bloodPressure');

        const heartRateValue = document.getElementById('heartRateValue');
        const breathingRateValue = document.getElementById('breathingRateValue');
        const bloodPressureValue = document.getElementById('bloodPressureValue');

        switch(condition) {
            case 'asma':
                heartRateSlider.value = 100;
                breathingRateSlider.value = 30;
                bloodPressureSlider.value = 130;
                break;
            case 'infarto':
                heartRateSlider.value = 120;
                breathingRateSlider.value = 35;
                bloodPressureSlider.value = 150;
                break;
            case 'hipoxia':
                heartRateSlider.value = 130;
                breathingRateSlider.value = 40;
                bloodPressureSlider.value = 140;
                break;
            case 'hiperventilacion':
                heartRateSlider.value = 110;
                breathingRateSlider.value = 25;
                bloodPressureSlider.value = 135;
                break;
            default:
                break;
        }

        heartRateValue.innerText = heartRateSlider.value;
        breathingRateValue.innerText = breathingRateSlider.value;
        bloodPressureValue.innerText = bloodPressureSlider.value;
    }

    const resetButton = document.getElementById('resetButton');
    resetButton.addEventListener('click', function() {
        const heartRateSlider = document.getElementById('heartRate');
        const breathingRateSlider = document.getElementById('breathingRate');
        const bloodPressureSlider = document.getElementById('bloodPressure');

        const heartRateValue = document.getElementById('heartRateValue');
        const breathingRateValue = document.getElementById('breathingRateValue');
        const bloodPressureValue = document.getElementById('bloodPressureValue');

        heartRateSlider.value = 75;
        breathingRateSlider.value = 15;
        bloodPressureSlider.value = 120;

        heartRateValue.innerText = heartRateSlider.value;
        breathingRateValue.innerText = breathingRateSlider.value;
        bloodPressureValue.innerText = bloodPressureSlider.value;
    });

    // Add an event listener to the blood pressure slider to update its display value
    const bloodPressureSlider = document.getElementById('bloodPressure');
    const bloodPressureValue = document.getElementById('bloodPressureValue');
    bloodPressureSlider.addEventListener('input', function() {
        bloodPressureValue.innerText = bloodPressureSlider.value;
    });
</script>
<audio id="heartbeatAudio" loop="">
<source src="/mnt/data/Latidos del corazón aceleración (Efecto de Sonido) Heartbeat speeding up sound effect.mp3" type="audio/mpeg"/>
    Your browser does not support the audio element.
</audio>
<script>
    const heartbeatAudio = document.getElementById('heartbeatAudio');
    const heartRateControl = document.getElementById('heartRate');
    
    heartRateControl.addEventListener('input', function() {
        const bpm = this.value;
        const playbackRate = bpm / 75;  // Assuming the default bpm of the audio is for 75bpm
        heartbeatAudio.playbackRate = playbackRate;
        heartbeatAudio.play();
    });
</script>
<script>
    const heartbeatAudio = document.getElementById('heartbeatAudio');
    const heartRateSlider = document.getElementById('heartRate');

    heartRateSlider.addEventListener('input', function() {
        const bpm = this.value;
        const playbackRate = bpm / 75;  // Assuming the default audio plays at a rate of 75 beats per minute
        heartbeatAudio.playbackRate = playbackRate;
        if (heartbeatAudio.paused) {
            heartbeatAudio.play();
        }
    });
</script>
</body>
</html>
