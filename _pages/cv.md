---
layout: archive
title: "Biography"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<style>
.bio-section {
  margin-bottom: 0.8em;
  background: #f8fafc;
  border-radius: 10px;
  padding: 1.2em 1.4em;
  border: 1px solid #e2e8f0;
}
.bio-entry {
  display: flex;
  gap: 1.2em;
  margin-bottom: 1em;
  align-items: flex-start;
}
.bio-entry:last-child {
  margin-bottom: 0;
}
.bio-date {
  min-width: 110px;
  font-size: 0.8em;
  color: #94a3b8;
  font-weight: 500;
  padding-top: 0.2em;
  white-space: nowrap;
}
.bio-body {
  flex: 1;
  min-width: 0;
}
.bio-body strong {
  display: block;
  font-size: 0.95em;
  color: #1e293b;
  font-weight: 600;
  margin-bottom: 0.1em;
}
.bio-org {
  display: flex;
  align-items: center;
  justify-content: space-between;
  width: 100%;
  gap: 0.75em;
  margin-bottom: 0.12em;
}
.bio-org strong {
  flex: 1;
  min-width: 0;
  order: 1;
  margin: 0;
}
.bio-org .bio-mark {
  order: 2;
}
.bio-body span {
  font-size: 0.85em;
  color: #64748b;
}
.bio-mark {
  width: 1.95em;
  height: 1.95em;
  min-width: 1.95em;
  display: inline-flex;
  align-items: center;
  justify-content: center;
  padding: 0.18em;
  background: #ffffff;
  border: 1px solid #cbd5e1;
  box-shadow: 0 1px 3px rgba(15, 23, 42, 0.16);
}
.bio-mark img {
  width: 100%;
  height: 100%;
  object-fit: contain;
  display: block;
}
.bio-mark--school {
  border-radius: 999px;
}
.bio-mark--company {
  border-radius: 0.52em;
}
.bio-section-title {
  display: flex;
  align-items: center;
  gap: 0.5em;
  font-size: 0.75em;
  font-weight: 700;
  text-transform: uppercase;
  letter-spacing: 0.1em;
  color: #2563eb;
  margin-bottom: 1em;
  padding-bottom: 0.6em;
  border-bottom: 1px solid #e2e8f0;
}
.bio-section-title i {
  font-size: 0.95em;
}
.skill-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 0.5em;
}
.skill-tag {
  background: #eff6ff;
  color: #2563eb;
  border: 1px solid #bfdbfe;
  border-radius: 20px;
  padding: 0.25em 0.85em;
  font-size: 0.82em;
  font-weight: 500;
}
.resume-block {
  background: #f8fafc;
  border: 1px solid #e2e8f0;
  border-radius: 10px;
  padding: 1em 1.4em;
  margin-bottom: 0.8em;
  font-size: 0.95em;
}

/* Dark mode overrides */
html.dark-mode .bio-section,
html.dark-mode .resume-block {
  background: #1e293b;
  border-color: #334155;
}
html.dark-mode .bio-section-title {
  color: #60a5fa;
  border-bottom-color: #334155;
}
html.dark-mode .bio-body strong {
  color: #f1f5f9;
}
html.dark-mode .bio-body span,
html.dark-mode .bio-date {
  color: #94a3b8;
}
html.dark-mode .bio-mark {
  background: #f8fafc;
  border-color: #475569;
  box-shadow: none;
}
html.dark-mode .skill-tag {
  background: #1e3a5f;
  color: #93c5fd;
  border-color: #1d4ed8;
}
html.dark-mode .bio-entry {
  border-bottom-color: #334155;
}
</style>


<div class="bio-section">
  <div class="bio-section-title"><i class="fas fa-graduation-cap"></i> Education</div>
  <div class="bio-entry">
    <div class="bio-date">2020 – 2026</div>
    <div class="bio-body">
      <div class="bio-org">
        <span class="bio-mark bio-mark--school">
          <img src="{{ base_path }}/images/logos/msu-school.ico" alt="Michigan State University logo" loading="lazy" decoding="async">
        </span>
        <strong>Ph.D. in Computer Science</strong>
      </div>
      <span>Michigan State University · East Lansing, MI</span>
    </div>
  </div>
  <div class="bio-entry">
    <div class="bio-date">2016 – 2019</div>
    <div class="bio-body">
      <div class="bio-org">
        <span class="bio-mark bio-mark--school">
          <img src="{{ base_path }}/images/logos/ncepu-school.ico" alt="North China Electric Power University logo" loading="lazy" decoding="async">
        </span>
        <strong>M.Eng. in Electrical Engineering</strong>
      </div>
      <span>North China Electric Power University · Beijing, China</span>
    </div>
  </div>
  <div class="bio-entry">
    <div class="bio-date">2012 – 2016</div>
    <div class="bio-body">
      <div class="bio-org">
        <span class="bio-mark bio-mark--school">
          <img src="{{ base_path }}/images/logos/xjtu-school.png" alt="Xi'an Jiaotong University logo" loading="lazy" decoding="async">
        </span>
        <strong>B.Eng. in Electrical Engineering</strong>
      </div>
      <span>Xi'an Jiaotong University · Xi'an, China</span>
    </div>
  </div>
</div>

<div class="bio-section">
  <div class="bio-section-title"><i class="fas fa-briefcase"></i> Professional Experience</div>
  <div class="bio-entry">
    <div class="bio-date">Sep – Dec 2025</div>
    <div class="bio-body">
      <div class="bio-org">
        <span class="bio-mark bio-mark--company">
          <img src="{{ base_path }}/images/logos/dolby.svg" alt="Dolby logo" loading="lazy" decoding="async">
        </span>
        <strong>Multimodal Trustworthy AI Research Intern</strong>
      </div>
      <span>Dolby Laboratories · Sunnyvale, CA</span>
    </div>
  </div>
  <div class="bio-entry">
    <div class="bio-date">Feb – Jul 2025</div>
    <div class="bio-body">
      <div class="bio-org">
        <span class="bio-mark bio-mark--company">
          <img src="{{ base_path }}/images/logos/bytedance.svg" alt="ByteDance logo" loading="lazy" decoding="async">
        </span>
        <strong>AI Security Research Scientist Intern</strong>
      </div>
      <span>ByteDance Inc. · San Jose, CA</span>
    </div>
  </div>
  <div class="bio-entry">
    <div class="bio-date">Sep – Dec 2022</div>
    <div class="bio-body">
      <div class="bio-org">
        <span class="bio-mark bio-mark--company">
          <img src="{{ base_path }}/images/logos/samsung.svg" alt="Samsung logo" loading="lazy" decoding="async">
        </span>
        <strong>Research Scientist Intern</strong>
      </div>
      <span>Samsung Research America · Mountain View, CA</span>
    </div>
  </div>
</div>

<div class="bio-section">
  <div class="bio-section-title"><i class="fas fa-code"></i> Skills</div>
  <div class="skill-tags">
    <span class="skill-tag">Python</span>
    <span class="skill-tag">C++</span>
    <span class="skill-tag">PyTorch</span>
    <span class="skill-tag">TensorFlow</span>
    <span class="skill-tag">Multimodal AI</span>
    <span class="skill-tag">AI Security</span>
    <span class="skill-tag">LLM</span>
    <span class="skill-tag">Audio Processing</span>
  </div>
</div>

<div class="bio-section">
  <div class="bio-section-title"><i class="fas fa-users"></i> Service & Leadership</div>
  <div class="bio-entry">
    <div class="bio-date">2020 – 2022</div>
    <div class="bio-body">
      <strong>Vice President</strong>
      <span>MSU Badminton Club · Michigan State University</span>
    </div>
  </div>
</div>
