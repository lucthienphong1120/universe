<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta author="Luc Thien Phong">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Universe</title>
</head>
<style>
    body {
        overflow: hidden;
        margin: 0;
    }

    #word img {
        width: 100px;
        position: absolute;
        margin: 10;
    }
</style>

<body>
    <div id="word">
        <a href="https://www.crf-blogger.gq/">
            <img width="300" src="https://cdn.ltp110.tk/images/logo/logo.jpg" title="ltp" />
        </a>

    </div>

    <script type="module">
        import * as THREE from "https://cdn.skypack.dev/three@0.136.0";
        import { OrbitControls } from "https://cdn.skypack.dev/three@0.136.0/examples/jsm/controls/OrbitControls";

        var defined = 'QXV0aG9yOiBMdWMg';
        var datacenter = ['aHR0cHM6L', 'y93d3cuZmF', 'jZWJvb2suY29t'];
        let scene = new THREE.Scene();
        scene.background = new THREE.Color('#160016');
        let camera = new THREE.PerspectiveCamera(60, innerWidth / innerHeight, 1, 1000);
        camera.position.set(0, 4, 21);
        let renderer = new THREE.WebGLRenderer();
        renderer.setSize(innerWidth, innerHeight);
        document.body.appendChild(renderer.domElement);
        window.addEventListener("resize", event => {
            camera.aspect = innerWidth / innerHeight;
            camera.updateProjectionMatrix();
            renderer.setSize(innerWidth, innerHeight);
        })
        datacenter.push('L3Byb2ZpbGUu');
        let controls = new OrbitControls(camera, renderer.domElement);
        controls.enableDamping = true;
        controls.enablePan = false;
        datacenter.push('cGhwP2lkPTEw');
        let gu = {
            time: { value: 0 }
        }
        defined = defined.concat('VGhpZW4gUGhvbmc=');
        let sizes = [];
        let shift = [];
        let pushShift = () => {
            shift.push(
                Math.random() * Math.PI,
                Math.random() * Math.PI * 2,
                (Math.random() * 0.9 + 0.1) * Math.PI * 0.1,
                Math.random() * 0.9 + 0.1
            );
        }
        datacenter.push('MDA0NTQwNj');
        var context = atob(defined);
        let pts = new Array(50000).fill().map(p => {
            sizes.push(Math.random() * 1.5 + 0.5);
            pushShift();
            return new THREE.Vector3().randomDirection().multiplyScalar(Math.random() * 0.5 + 9.5);
        })
        for (let i = 0; i < 100000; i++) {
            let r = 10, R = 40;
            let rand = Math.pow(Math.random(), 1.5);
            let radius = Math.sqrt(R * R * rand + (1 - rand) * r * r);
            pts.push(new THREE.Vector3().setFromCylindricalCoords(radius, Math.random() * 2 * Math.PI, (Math.random() - 0.5) * 2));
            sizes.push(Math.random() * 1.5 + 0.5);
            pushShift();
        }
        console.log(context);
        datacenter.push('I2MTQ5MQ' + '==');
        let g = new THREE.BufferGeometry().setFromPoints(pts);
        g.setAttribute("sizes", new THREE.Float32BufferAttribute(sizes, 1));
        g.setAttribute("shift", new THREE.Float32BufferAttribute(shift, 4));
        let m = new THREE.PointsMaterial({
            size: 0.125,
            transparent: true,
            depthTest: false,
            blending: THREE.AdditiveBlending,
            onBeforeCompile: shader => {
                shader.uniforms.time = gu.time;
                shader.vertexShader = `
                    uniform float time;
                    attribute float sizes;
                    attribute vec4 shift;
                    varying vec3 vColor;
                    ${shader.vertexShader}
                `.replace(
                    `gl_PointSize = size;`,
                    `gl_PointSize = size * sizes;`
                ).replace(
                    `#include <color_vertex>`,
                    `#include <color_vertex>
                    float d = length(abs(position) / vec3(40., 10., 40));
                    d = clamp(d, 0., 1.);
                    vColor = mix(vec3(42,40,154), vec3(209,124,196), d) / 255.;
                `).replace(
                        `#include <begin_vertex>`,
                        `#include <begin_vertex>
                    float t = time;
                    float moveT = mod(shift.x + shift.z * t, PI2);
                    float moveS = mod(shift.y + shift.z * t, PI2);
                    transformed += vec3(cos(moveS) * sin(moveT), cos(moveT), sin(moveS) * sin(moveT)) * shift.a;
                `);
                // console.log(shader.vertexShader);
                shader.fragmentShader = `
                varying vec3 vColor;
                ${shader.fragmentShader}
                `.replace(
                    `#include <clipping_planes_fragment>`,
                    `#include <clipping_planes_fragment>
                    float d = length(gl_PointCoord.xy - 0.5);
                    if (d > 0.5) discard;
                `).replace(
                        `vec4 diffuseColor = vec4( diffuse, opacity );`,
                        `vec4 diffuseColor = vec4( vColor, smoothstep(0.5, 0.1, d) );`
                    );
                // console.log(shader.fragmentShader);
            }
        });
        let p = new THREE.Points(g, m);
        p.rotation.order = "ZYX";
        p.rotation.z = 0.2;
        scene.add(p)
        const data = atob(datacenter.join(''));
        let clock = new THREE.Clock();
        console.log(data);
        renderer.setAnimationLoop(() => {
            controls.update();
            let t = clock.getElapsedTime() * 0.5;
            gu.time.value = t * Math.PI;
            p.rotation.y = t * 0.05;
            renderer.render(scene, camera);
        });
    </script>
</body>

</html>
