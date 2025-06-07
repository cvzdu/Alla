const heart = new Nextparticle({
  renderer: 'webgl',
  image: document.querySelector('#valentines'),
  width: window.innerWidth,
  height: window.innerHeight,
  particleGap: 3,
  particleSize: 2,
  mouseForce: 5,
  noise: 0.2,
  layerCount: 3,
  layerDistance: 30
});
