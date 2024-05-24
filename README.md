# gesture-guard-1

# Gesture Guard

- [Gesture Guard](#gesture-guard)
  - [About project](#about-project)
    - [Techs used](#techs-used)
    - [Project Structure](#project-structure)
    - [Dependencies](#dependencies)
   - [Deployment](#deployment)

## About project

### Techs used

- TensorFlow
- PoseNet
- P5.js
- BlazePose

### Project Structure

```bash
.
├── index.html
├── about.html
├── files.html
├── contact.html
├── posenet.html
├──css
│   ├── style.css
│   └── animate.min
├── README.md
├── img
├── fonts
└── js

4 directories, 26 files
```

### Dependencies

| Dependency |                                      |
| :--------- | :----------------------------------: |
| TensorFlow |          Image Recognition           |
| Posenet    |          Points notations            |
| Blazepose  |          Handles navigation          |


## Deployment

Currently, deployment is handled by Github. Pushing code to `dev branch` will automatically trigger a deploy.

[![Github Status](https://api.netlify.com/api/v1/badges/bd039447-bb78-4d60-bcbb-a9a30fbb51c4/deploy-status)](https://app.netlify.com/sites/dev-portfolio-venkivijay/deploys)
