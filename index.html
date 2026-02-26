<!DOCTYPE html>
<html lang="cs">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GitHub Stream Test</title>
    
    <link href="https://vjs.zencdn.net/8.10.0/video-js.css" rel="stylesheet" />
    
    <style>
        body { margin: 0; background: #000; color: #fff; font-family: sans-serif; display: flex; flex-direction: column; align-items: center; justify-content: center; height: 100vh; }
        .container { width: 90%; max-width: 900px; }
        .vjs-matrix.video-js { border: 2px solid #3498db; box-shadow: 0 0 20px rgba(52, 152, 219, 0.5); }
        .info { margin-top: 20px; color: #94a3b8; font-size: 14px; text-align: center; }
    </style>
</head>
<body>

<div class="container">
    <video-js id="my-video" class="vjs-default-skin vjs-big-play-centered vjs-16-9" controls preload="auto" width="640">
        <source src="http://188.175.250.66/dash/CH_NOVA_SPORT1_HD.ism/playlist.mpd" type="application/dash+xml">
    </video-js>
</div>

<div class="info">
    Testování streamu: Nova Sport 1 HD (DASH)<br>
    Identifikace: stremujeme.to/9.8
</div>

<script src="https://vjs.zencdn.net/8.10.0/video.min.js"></script>

<script>
    // Konfigurace přehrávače
    const player = videojs('my-video', {
        html5: {
            vhs: {
                overrideNative: true
            },
            dash: {
                // TADY JE TA MAGIE S USER-AGENTEM
                setHttpHeaders: {
                    'User-Agent': 'stremujeme.to/9.8 (Linux;Android 14) AndroidXMedia3/1.1.1'
                }
            }
        }
    });

    player.ready(function() {
        console.log('Přehrávač je připraven. Zkouším načíst stream...');
        this.play(); // Pokus o automatické spuštění
    });

    // Výpis chyb pro diagnostiku
    player.on('error', function() {
        console.error('Chyba přehrávače:', player.error());
    });
</script>

</body>
</html>
