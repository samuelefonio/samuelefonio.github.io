---
layout: page
permalink: /repositories/
title: Repositories
description: Here are my selected github repositories. They can be divided in academic and personal ones. For each personal one, you can find a related project description in the Project page.
nav: true
nav_order: 4
---

# Academic projects repositories

Here is a list of the Academic Projects I have been involved in. 

## Fed2RC
In this work, we have developed a technique for federated time series classification based on Rocket features. Rocket is a method that exploits random mappings to accomplish time series classification tasks, and it is based on random kernel selection. We developed a FL system that shares only the generator of the random kernel and finds a closed-form solution for the general Ridge classifier, improving communication cost, computation cost and performances.
[GitHub](https://github.com/CasellaJr/Fed2RC)

---

## Hyperbolic Benchmark
In this work, we have benchmarked different geometries, answering one key question: when do hyperbolic geometries give you something for free? Not often. We found that, differently from what said by many papers, hyperbolic spaces are not magical, and they don't bring improvements if not specifically tailored. We benchmarked several metric: accuracy, robustness and OOD detection in image classification.
[GitHub](https://github.com/samuelefonio/proto_bench)

---

## Personalized Aggregation for Federated Prototypical Learning
In this work, we developed a Federated Learning strategy to optimize Federated systems that exchange only prototypes under adversarial conditions, i.e. with model poisoning attacks. We have introduced a novel technique to prevent these type of attacks and considered usually neglected metrics, i.e. fairness.
[GitHub](https://github.com/samuelefonio/Personalized-Aggregation-For-Federated-Prototypical-Learning)

---

## Hyperbolic Prototypical Entailment Cones
In this work, we have introduced a novel hyperbolic method based on Hyperbolic Entailment Cones to improve the performances of Hyperbolic Representation Learning techniques using prototype learning. In particular, we have introduced a novel metric based on entailment cones to learn and a novel clipping technique called backclip.
[GitHub](https://github.com/samuelefonio/HPEC)


---

## fluke
Federated Learning Utility frameworK for Experimentationg is our framework used for experimenting and fast prototyping of novel FL techniques. My main part in this project has been testing and improvements.
[GitHub](https://github.com/makgyver/fluke)

---

## Federated Survival Analysis
In this work, we have developed an adaptation of Adaboost.F to survival analysis in a FL context, which required redesigning some part of the original algorithm, and which outperformed the state-of-the-art methods in FL survival analysis.
[GitHub](https://github.com/oussamaHarrak/FederatedSurv)

---

## Parallel Interior Point Solver
We implemented an interior point solver (Karmarkar's Interior Point method) and compared its implementation under different parallel settings: MPI, PSTL, CUDA. While achieving the best performance with tailored CUDA code, using PSTL made the code easily portable from CPU-only regimes to GPUs, while CUDA requested a complete code revision. 
[GitHub](https://github.com/alpha-unito/parallel-interior-point-solver)


# Personal projects repositories

Here is a list of the Personal Projects I have done for personal purposes. 

## Taiwanese Credit Risk
In this project we implemented a credit risk model trying to predict wether a customer could return a loan or not. We benchmarked many ML algorithms and conducted carefull EDA.
[GitHub](https://github.com/samuelefonio/Taiwan_credit_risk)

## Digital Wallet Transactions
In this project I implemented a full end-to-end ML pipeline, including EDA, model development for fraud detection and an interface using fastAPI and Streamlit. 
[GitHub](https://github.com/samuelefonio/Digital-Wallet-Transaction)


---

# More
For a complete and up-to-date list of repositories, visit my  
[GitHub profile](https://github.com/samuelefonio)

<!-- {% if site.data.repositories.github_users %}

## GitHub users

<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for user in site.data.repositories.github_users %}
    {% include repository/repo_user.liquid username=user %}
  {% endfor %}
</div>

---

{% if site.repo_trophies.enabled %}
{% for user in site.data.repositories.github_users %}
{% if site.data.repositories.github_users.size > 1 %}

  <h4>{{ user }}</h4>
  {% endif %}
  <div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% include repository/repo_trophies.liquid username=user %}
  </div>

---

{% endfor %}
{% endif %}
{% endif %}

{% if site.data.repositories.github_repos %}

## GitHub Repositories

<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for repo in site.data.repositories.github_repos %}
    {% include repository/repo.liquid repository=repo %}
  {% endfor %}
</div>
{% endif %} -->
