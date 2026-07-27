SUPER CONVERTER // MK-VI
In Loving Memory of My Father
He taught me how to think, how to troubleshoot, and how to solve problems from the ground up. This engine is dedicated to him—the only one who always had my back.

Overview
Super Converter is a high-performance, framework-less, client-side universal audio conversion workstation built entirely from scratch using native Web APIs. Designed with zero DOM layout dependencies, it features a 100% pure canvas rendering pipeline running at a smooth 60 FPS, complete with an industrial gunmetal chassis, glowing vector waveforms, and an async non-blocking audio codec architecture.

Engineering Architecture
Pure Canvas GUI: Zero HTML/CSS layout elements. Every interactive button, dropdown menu, metadata panel, and border is dynamically calculated and rendered via the HTML5 2D Canvas context.

Asynchronous Chunked Codecs: Heavy mathematical audio processing (such as real-time MPEG Layer III compression via LAME.js) is sliced into non-blocking micro-batches using zero-delay event loops. This ensures the UI never freezes, maintaining fluid 60 FPS rendering during heavy computations.

Dynamic Industrial Matrix: Procedural background engine featuring a two-tier orthogonal grid, autonomous 90-degree glowing data traces, pulsing grid tiles, and atmospheric floating debris.

Universal Browser Ingestion: Decodes any audio or video container format supported by the browser engine (AudioContext.decodeAudioData()), turning raw binary streams into editable PCM buffers.

Supported Formats
Inputs: MP3, WAV, OGG, FLAC, AAC, WebM, MP4 (Any browser-decodable audio/video container stream).

Outputs:

WAV: Uncompressed 16-bit PCM.

MP3: True MPEG Layer III (192kbps high-fidelity encoding via integrated LAME engine).

WebM / Ogg: Real-time stream capture via the browser MediaRecorder API.

Local Deployment & Usage
Save the application script as index.html.

Open the file directly in any modern web browser (ChromeOS, Chrome, Firefox, or Edge). No web server, Node.js modules, or external build toolchains required.

Drag and drop any audio or video file onto the industrial drop zone, select your target output stream from the custom canvas dropdown, and hit Execute Conversion to run the async pipeline with live progress tracking.

Built with vanilla JavaScript, HTML5 Canvas, and the Web Audio API.
