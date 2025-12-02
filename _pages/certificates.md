---
layout: archive
title: "Certificates"
permalink: /certificates/
author_profile: true
---

{% include base_path %}

<style>
  .certificate-grid {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 50px;
    margin: 20px 0;
    max-width: 800px;
  }
  .certificate-item {
    text-align: center;
    cursor: pointer;
    text-decoration: none;
    color: inherit;
    display: block;
  }
  .certificate-item img {
    width: 220px;
    height: auto;
    margin-bottom: 15px;
    display: block;
    margin-left: auto;
    margin-right: auto;
    transition: transform 0.3s ease, opacity 0.3s ease;
  }
  .certificate-item:hover img {
    transform: scale(1.05);
    opacity: 0.85;
  }
  .certificate-item .caption {
    font-size: 16px;
    font-weight: bold;
    margin-top: 10px;
    transition: color 0.3s ease;
  }
  .certificate-item:hover .caption {
    color: #0066cc;
  }
</style>

<div class="certificate-grid">
  <a href="https://www.credly.com/badges/f02d1cda-dbd7-4a68-8e94-38f5513a38f2" class="certificate-item">
    <img src="../images/aws_ml.png" alt="Machine Learning Engineer"/>
    <div class="caption">Machine Learning Engineer</div>
  </a>

  <a href="https://www.credly.com/badges/96bf6cff-a8dd-405b-83fa-b3a468c1c1aa/public_url" class="certificate-item">
    <img src="../images/aws_dv.png" alt="AWS Developer Associate"/>
    <div class="caption">AWS Developer Associate</div>
  </a>
  
  <a href="https://www.credly.com/badges/77aae646-47d9-46ea-a38b-a177b307bcbe/public_url" class="certificate-item">
    <img src="../images/aws_de.png" alt="AWS Data Engineer Associate"/>
    <div class="caption">AWS Data Engineer Associate</div>
  </a>
  
  <a href="https://www.credly.com/badges/41951d72-d841-4a7f-8927-d64a4428f162/public_url" class="certificate-item">
    <img src="../images/aws_sa.png" alt="AWS Solutions Architect Associate"/>
    <div class="caption">AWS Solutions Architect Associate</div>
  </a>
  
  <a href="https://graphacademy.neo4j.com/c/4bbe6414-788d-4ca7-854c-0c938f80a26f/" class="certificate-item">
    <img src="../images/neo4j.png" alt="Neo4j Certified Professional"/>
    <div class="caption">Neo4j Certified Professional</div>
  </a>
</div>



