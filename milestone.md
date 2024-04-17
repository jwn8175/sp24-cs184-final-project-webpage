---
layout: default
title: Project Milestone
parent: Home
nav_order: 3
---

# Project Milestone Report
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

- TOC
{:toc}

## Progress Summary

To incorporate our filter ideas into the graphics pipeline, we decided to first bind the target image as a texture input to the shader program, and then do all of our filtering color computations in the fragment shader. Our program is set up in python, using the `moderngl` and `moderngl-window` packages to execute our shader program and render outputs.

Setting up the project boilerplate and learning how to use the packages took a fair amount of time, but we were able to fully implement both the square and circle variants of the Kuwahara. Our remaining goals are the same as before - implementing the anisotropic variant of the Kuwahara filter and also the Voronoi filters. We also have a new stretch goal, which is to create a functioning GUI that allows the user to toggle between different kernel sizes so they can visualize the filters in action.

### Image Outputs

Here are some sample images that our current filters produced. The images were all rendered with a filter kernel size of 10.

Jay's Pet Dachshund Coco

<div style="display: flex; justify-content: center">
    <table style="width: 100%">
        <tr>
            <td>
                <div style="display: flex; justify-content: center">
                    <figure>
                        <img
                            src="./milestone_assets/coco_original.png"
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
                            src="./milestone_assets/coco_kuwahara_square.png"
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
                            src="./milestone_assets/coco_kuwahara_circle.png"
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

Boat from the Seattle Chihuly Garden and Glass Exhibit

<div style="display: flex; justify-content: center">
    <table style="width: 100%">
        <tr>
            <td>
                <div style="display: flex; justify-content: center">
                    <figure>
                        <img
                            src="./milestone_assets/boat_original.png"
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
                            src="./milestone_assets/boat_kuwahara_square.png"
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
                            src="./milestone_assets/boat_kuwahara_circle.png"
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

## Video

[Video Link](https://drive.google.com/file/d/1sLObNYw-nIJ1GNPIj1fNxYOUnrUL1MfX/view?usp=sharing)

## Presentation

[Presentation Link](https://docs.google.com/presentation/d/1u7DSpc-4jHmdkemrlDypntjhXeuUKlT2smvcd4eiiBs/edit?usp=sharing)
