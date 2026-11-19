# Robotics 101: Kinematics and Inverse Kinematics

A structured collection of course materials for learning robot kinematics, covering the fundamentals from basic robot configurations and coordinate frames through forward kinematics and inverse kinematics.

These PDFs preserve the notes and worked examples from **NSM Robotics**. I enjoyed learning this subject through the channel, especially its clear treatment of matrices, transformations, and the mathematics behind robotic motion. The YouTube channel is no longer available, so this repository keeps the course material accessible for students and lifelong learners.

## What You Will Learn

The course progresses from introductory robotics concepts to spatial transformations and manipulator kinematics:

- Types of robot and common coordinate configurations
- Coordinate frames and spatial descriptions
- Mapping and transformations between frames
- Rotation and translation matrices
- Forward kinematics
- Link-frame assignments and Denavit-Hartenberg (DH) conventions
- Homogeneous transformation matrices
- Manipulator pose calculation
- Inverse kinematics
- Analytical and numerical approaches to finding joint solutions

## Course Materials

| Unit | Topic | Pages | Material |
|---|---|---:|---|
| Unit 1 | Introduction and Robotics Basics | 65 | [Robotics 101 UNIT 1.pdf](./Robotics%20101%20UNIT%201.pdf) |
| Unit 2 | Coordinate Frames, Mapping, and Transforms | 111 | [Robotics 101 UNIT 2.pdf](./Robotics%20101%20UNIT%202.pdf) |
| Unit 3 | Forward Kinematics | 94 | [Robotics-101-UNIT-3.pdf](./Robotics-101-UNIT-3.pdf) |
| Unit 4 | Inverse Kinematics | 70 | [Robotics-101-UNIT-4.pdf](./Robotics-101-UNIT-4.pdf) |

The PDFs contain a combined total of **340 pages**.

### Unit 1: Introduction and Basics

Covers an introduction to robotics and common robot configuration styles, including:

- Cartesian coordinate robots
- Cylindrical robots
- Spherical or polar coordinate robots
- Jointed-arm, articulated, and revolute robots
- SCARA robots
- Other practical considerations in introductory robotics

### Unit 2: Coordinate Frames, Mapping, and Transforms

Builds the geometric foundation needed for robot kinematics:

- Coordinate and reference frames
- Representations of position and orientation
- Mapping between coordinate systems
- Rotation and translation
- Homogeneous transformations
- Composition of successive transforms

### Unit 3: Forward Kinematics

Explains how to determine the position and orientation of a manipulator's end effector from known joint variables:

- Frames attached to adjacent robot links
- Link-frame conventions
- The relationship between joint parameters and link transformations
- Denavit-Hartenberg parameters
- DH parameter tables
- Multiplication of homogeneous transformation matrices

### Unit 4: Inverse Kinematics

Introduces the problem of finding joint variables from a desired end-effector position and orientation:

- Forward and inverse kinematics relationships
- Position and orientation constraints
- Analytical solutions for suitable manipulators
- Numerical solution methods
- Multiple, redundant, or unreachable solutions

## Recommended Learning Sequence

Work through the units in order:

1. Read **Unit 1** to understand robot types and terminology.
2. Study **Unit 2** carefully, since coordinate frames and matrix transformations are the foundation of all later work.
3. Apply those transformations in **Unit 3** to calculate forward kinematics.
4. Reverse the process in **Unit 4** to understand inverse kinematics.

For each worked example, redraw the frames, write the transformation matrices, and check the result by substituting the joint values back into forward kinematics.

## Prerequisites

A basic understanding of the following areas is helpful:

- Matrices and matrix multiplication
- Coordinate geometry
- Trigonometry
- Vectors
- Basic calculus
- Basic linear algebra

No software is required to read the course materials. You may optionally use MATLAB, Octave, Python with NumPy, or a symbolic mathematics package to verify examples and perform matrix calculations.

## How to Use This Repository

Clone the repository and open the PDFs locally:

```bash
git clone https://github.com/Asim-Shah-web/Robotics-101-KINEMATICS.git
cd Robotics-101-KINEMATICS
```

Then open the units in the following order:

- `Robotics 101 UNIT 1.pdf`
- `Robotics 101 UNIT 2.pdf`
- `Robotics-101-UNIT-3.pdf`
- `Robotics-101-UNIT-4.pdf`

## Repository Structure

```text
.
├── Robotics 101 UNIT 1.pdf
├── Robotics 101 UNIT 2.pdf
├── Robotics-101-UNIT-3.pdf
└── Robotics-101-UNIT-4.pdf
```

## Archive and Attribution

This repository is an educational archive of the course materials associated with **NSM Robotics**. The channel and its original video lessons are no longer available on YouTube.

The PDFs are the primary resource in this repository. If you find an error or ambiguity, verify it against another robotics text and contribute a correction when appropriate.

## Contributing

Contributions are welcome, especially:

- Fixing broken links or document descriptions
- Improving the course index
- Adding an errata file for mathematical or notation mistakes
- Adding worked examples or small simulation code
- Improving accessibility by providing text or searchable versions of the PDFs

Please keep additions directly related to the course and clearly distinguish original material from community contributions.
