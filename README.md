## Brief Reverse Correlation Task

In this repository you can find a version of the Brief Reverse Correlation Task that you can run locally on your computer (or host online if you know your way around servers and databases, e.g., netlify).

The Brief Reverse Correlation (Brief-RC) task, introduced by Schmitz et al. (2024), is an innovative method for capturing visual facial representations of social categories. It addresses the limitations of traditional psychophysical reverse correlation methods, which require numerous trials (300 to 1000s) to generate classification images (CIs) of acceptable quality. By increasing the number of stimuli ("noisy faces") presented in each trial, the Brief-RC task improves the quality of individual and average CIs while reducing the overall task length. This efficiency makes it a highly valuable tool for social psychology research, by enabling researchers to use the RC paradigm with less resources (all thanks to the team of Schmitz and collaborators, 2024).


**Running the Experiment Locally:**

1. **Download** the HTML file (e.g., `demo_briefrc_12_ENG.html`) and the `images` folder containing the task stimuli.
2. **Place** both the HTML file and the `images` folder in the same directory on your computer.
3. **Run** the experiment by opening the HTML file in your web browser.

The results will be automatically saved to your browser's default downloads directory (usually a folder called Downloads) upon completion.

**Experiment Versions:**

*   **Standard Version:** `demo_briefrc_12_ENG.html`
*   **Version with Stimulus Verification:** `demo_filename_check_briefrc_12_ENG.html`

This version displays the filenames of the images during the experiment. Use this version to verify how the stimuli are presented and ensure proper counterbalancing.

## Face Stimuli

The task uses noise patches superimposed on a composite image of average male and female faces with neutral expression from the Karolinska Face Database (Lundqvist & Litton, 1998). This base face was generated using the rcicr R package (Dotsch, 2016).

## References

Dotsch R. (2016). Rcicr: Reverse-correlation image-classification toolbox. R package (Version 0.3), 4. [https://cran.r-project.org/web/packages/rcicr/index.html](https://cran.r-project.org/web/packages/rcicr/index.html)

Lundqvist, D., & Litton, J. E. (1998). The Averaged Karolinska Directed Emotional Faces - AKDEF, CD ROM from Department of Clinical Neuroscience, Psychology section, Karolinska Institutet, ISBN 91-630-7164-9.

Schmitz, M., Rougier, M., & Yzerbyt, V. (2024). Introducing the brief reverse correlation: An improved tool to assess visual representations. European Journal of Social Psychology. Advance Online Publication. https://doi.org/10.1002/ejsp.3100 


# About me

Manuel Oliveira

Working on topics related to Human-AI Interaction, AI in Education, Social Cognition

Personal website: <https://manueloliveira.nl/>
