---
layout: default
title: Project Milestone
parent: Home
---

# Project Milestone Report
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

- TOC
  {:toc}

## Progress Summary

To incorporate our filter ideas into the graphics pipeline, we decided to first bind the input image as a texture input to the shader program, and then do all of our filtering color computations in the fragment shader. We decided to set up our program in python, using the `moderngl` and `moderngl-window` packages to execute our shader program and render outputs.

Setting up the project boilerplate and learning how to use the packages took a fair amount of time, but we were able to fully implement both the square and circle variants of the Kuwahara.

### Image Outputs

<div style="display: flex; justify-content: center">
    <table style="width: 100%">
        <tr>
            <td>
                <div style="display: flex; justify-content: center">
                    <figure>
                        <img
                            src="./"
                            width="300px"
                        />
                        <figcaption>Original</figcaption>
                    </figure>
                </div>
            </td>
            <td>
                <div style="display: flex; justify-content: center">
                    <figure>
                        <img
                            src="./assets/bird_square.png"
                            width="300px"
                        />
                        <figcaption>Square</figcaption>
                    </figure>
                </div>
            </td>
        </tr>
        <br />
        <tr>
            <td>
                <div style="display: flex; justify-content: center">
                    <figure>
                        <img
                            src="./assets/bird_circle.png"
                            width="300px"
                        />
                        <figcaption>Circle</figcaption>
                    </figure>
                </div>
            </td>
        </tr>
        <br />
    </table>
</div>

### Notable Observations

## Video

Video Link Here

## Presentation

Presentation Link Here
