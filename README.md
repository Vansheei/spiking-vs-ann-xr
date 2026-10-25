# Same Weights, Two Brains

An interactive WebXR app for Meta Quest that shows how biological and artificial neurons compute differently.

A small network (784 → 64 → 10) is trained on MNIST handwritten digits. The exact same weights are then run in two ways. The AI side is a standard artificial neural network that answers instantly in a single pass. The brain side is a spiking neural network built from leaky integrate-and-fire neurons, where the answer builds up over time as spikes travel through the layers.

Users draw a digit in the air with the controller and watch both networks process it side by side. In lesion mode they can switch off neurons, like damage after a stroke, and compare how each network copes. A built-in experiment measures accuracy across increasing levels of damage.

Built during a VR/XR and AI hackathon with React, three.js, react-three-fiber, @react-three/xr and TensorFlow.js. Developed with Lovable, 3D models generated with Meshy.

## Development

Prefer working locally? You need Node.js and npm — [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating).

```sh
git clone <this-repository-url>
cd <repository-name>
npm i
npm run dev
```
