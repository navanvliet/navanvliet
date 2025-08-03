(DSAIE)=
# Cross-Over

In the DSAIE module, I learned how data science and machine learning can be applied to solve complex engineering problems. The course was divided into three parts: **Probabilistic Machine Learning**, **Deep Learning**, and a **hands-on project** on structural optimization.

```{admonition} 📚 Reading Material

<div style="display: flex; flex-wrap: wrap; gap: 1rem;">

  <div style="flex: 1 1 45%; border: 1px solid #ddd; border-radius: 8px; padding: 1rem;">
    <strong>C.M. Bishop</strong><br>
    Pattern Recognition and Machine Learning (2009), Springer  
    <div style="margin-top: 0.5rem;">
      <span style="background-color: #e63946; color: white; padding: 0.2rem 0.5rem; border-radius: 5px;">bishop-prml</span>
    </div>
  </div>

  <div style="flex: 1 1 45%; border: 1px solid #ddd; border-radius: 8px; padding: 1rem;">
    <strong>S.J.D. Prince</strong><br>
    Understanding Deep Learning (2023), MIT Press  
    <div style="margin-top: 0.5rem;">
      <span style="background-color: #f77f00; color: white; padding: 0.2rem 0.5rem; border-radius: 5px;">prince-udl</span>
    </div>
  </div>

  <div style="flex: 1 1 45%; border: 1px solid #ddd; border-radius: 8px; padding: 1rem;">
    <strong>I. Goodfellow et al.</strong><br>
    Deep Learning (2016), MIT Press  
    <div style="margin-top: 0.5rem;">
      <span style="background-color: #343a40; color: white; padding: 0.2rem 0.5rem; border-radius: 5px;">goodfellow-dl</span>
    </div>
  </div>

  <div style="flex: 1 1 45%; border: 1px solid #ddd; border-radius: 8px; padding: 1rem;">
    <strong>Extra resources</strong><br>
    MUDE content, other books  
    <div style="margin-top: 0.5rem;">
      <span style="background-color: #2a9d8f; color: white; padding: 0.2rem 0.5rem; border-radius: 5px;">extra-reading</span>
    </div>
  </div>

</div>
```
---

## 📊 Probabilistic Machine Learning

This part of the module focused on building a solid foundation in machine learning, with a strong emphasis on uncertainty quantification and probabilistic reasoning — which are particularly relevant for engineering applications. Topics we covered included:

- **Regression & Bayesian Regression** – Understanding how to model data with uncertainty and make predictions with confidence intervals.
- **Classification** – Developing models that can distinguish between categories in data, using probabilistic decision boundaries.
- **Kernel Methods & Gaussian Processes** – Applying powerful non-linear techniques to model complex relationships.
- **Clustering & Mixture Models** – Learning how to identify hidden patterns and groupings in data without supervision.
- **Dimensionality Reduction (PCA & Autoencoders)** – Reducing data complexity while retaining relevant features.

These concepts taught me to think critically about model assumptions and interpret predictions not just as outputs, but as probability-informed estimates.

---

## 🤖 Deep Learning

We explored the fundamentals of deep learning, starting with the **curse of dimensionality** and the importance of **inductive biases** in model architectures:

- **Convolutional Neural Networks (CNNs)** – Learning how spatial biases allow CNNs to recognize patterns in images and structured data.
- **Recurrent Layers & Sequential Bias** – Understanding how temporal or ordered data can be captured by deep models.
- **Advanced Architectures** – Including an introduction to **Graph Neural Networks**, **Transformers**, and **Physics-Informed Neural Networks** — all tailored to specific data types or physical contexts.

This part showed how deep neural networks can be adapted for various engineering applications, from computer vision to physics-based modeling.

---

## 🏗️ Project: Structural Optimization with Bayesian Techniques

In the final part of the course, we applied the theory in a project focused on **optimizing a truss structure** using **Bayesian optimization**. The challenge was to minimize the total weight of the structure, while ensuring it met **dynamic performance constraints** like minimum natural frequencies.

- We started with a fixed truss topology and a set of initial parameters (nodal coordinates and cross-sections).
- Using **Bayesian optimization**, we explored the high-dimensional design space efficiently, reducing the number of expensive FEM simulations needed.
- This taught me how probabilistic models (surrogates) can accelerate design exploration and lead to data-efficient engineering workflows.

This project tied together everything from the course — uncertainty modeling, machine learning, and structural mechanics — into a single real-world application.

The project can be found on Github here: [TRUSS](https://github.com/navanvliet/TRUSS1)  
_Credits for the clear Readme and code go to Javier Fuertes Guadarrama._

---
