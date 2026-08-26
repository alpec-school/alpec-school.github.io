---
title: "Program"
featured_image: "/images/backgrounds/_ALE1907.jpg"
position_vertical: 35%
menu:
  main:
    weight: 1
---


### SPEAKERS

<style>
.speaker-grid {
  display: flex;
  flex-direction: column;
  gap: 1.2em;
  margin: 1.5em 0 2.5em;
}

.speaker-card {
  background: #fff;
  border: 1px solid #ddd;
  border-radius: 8px;
  box-shadow: 0 2px 6px rgba(0,0,0,0.07);
  display: flex;
  flex-direction: row;
  overflow: hidden;
}

.speaker-card img {
  width: 160px;
  min-width: 160px;
  height: 180px;
  object-fit: cover;
  object-position: top;
  display: block;
}

.speaker-card-body {
  padding: 0.85em 1em 1em;
  display: flex;
  flex-direction: column;
  flex: 1;
}

@media (max-width: 600px) {
  .speaker-card {
    flex-direction: column;
  }
  .speaker-card img {
    width: 100%;
    min-width: unset;
    height: auto;
    object-fit: contain;
  }
}

.speaker-card-name {
  font-size: 0.97em;
  font-weight: 700;
  color: #0066cc;
  margin-bottom: 0.15em;
}

.speaker-card-name a {
  color: inherit;
  text-decoration: none;
}

.speaker-card-name a:hover {
  text-decoration: underline;
}

.speaker-card-affil {
  font-size: 0.78em;
  color: #666;
  margin-bottom: 0.75em;
  line-height: 1.35;
}

.speaker-card-talks {
  list-style: none;
  padding: 0;
  margin: 0;
  display: flex;
  flex-direction: column;
  gap: 0.45em;
}

.speaker-card-talks li {
  font-size: 0.82em;
}

.speaker-card-talks .talk-title {
  font-style: italic;
  font-weight: 600;
  color: #111;
}

.speaker-card-talks details.abstract {
  display: block;
  margin-top: 0.2em;
}

.speaker-card-talks details.abstract > summary {
  list-style: none;
  cursor: pointer;
  display: inline;
  font-size: 0.85em;
  font-style: normal;
  font-weight: normal;
  color: #0066cc;
  text-decoration: underline;
}
.speaker-card-talks details.abstract > summary::-webkit-details-marker { display: none; }
.speaker-card-talks details.abstract > summary::marker { content: ""; }
.speaker-card-talks details.abstract > summary::before { content: "Show abstract"; }
.speaker-card-talks details.abstract[open] > summary::before { content: "Hide abstract"; }

.speaker-card-talks details.abstract .abstract-text {
  display: block;
  margin-top: 0.4em;
  font-size: 0.88em;
  font-style: italic;
  font-weight: normal;
  color: #444;
  padding-left: 0.7em;
  border-left: 3px solid #ccc;
  line-height: 1.5;
}
</style>

<div class="speaker-grid">

  <div class="speaker-card">
    <img src="/images/speakers/caminata.avif" alt="Alessio Caminata">
    <div class="speaker-card-body">
      <div class="speaker-card-name"><a href="https://alessiocaminata.wixsite.com/alca">Alessio Caminata</a></div>
      <div class="speaker-card-affil">University of Genoa — Italy</div>
      <ul class="speaker-card-talks">
        <li>
          <span class="talk-title">Solving polynomial systems with Gröbner bases</span>
          <details class="abstract"><summary></summary>
            <div class="abstract-text">Many problems arising in cryptography can be modeled by systems of multivariate polynomial equations over a finite field. It is therefore important to understand how to solve such systems efficiently. Gröbner bases provide a fundamental tool for this purpose. In the first part of these lectures, we review and explain the connection between polynomial system solving and Gröbner bases, introducing important notions such as the Macaulay matrix. In the second part, we introduce the notions of solving degree, last fall degree, and degree of regularity, which are commonly used to study the complexity of polynomial systems arising in cryptography.</div>
          </details>
        </li>
      </ul>
    </div>
  </div>

  <div class="speaker-card">
    <img src="/images/speakers/marcolla.png" alt="Chiara Marcolla">
    <div class="speaker-card-body">
      <div class="speaker-card-name"><a href="https://scholar.google.com/citations?user=QuN8bAwAAAAJ&hl=it">Chiara Marcolla</a></div>
      <div class="speaker-card-affil">TII — Abu Dhabi, UAE</div>
      <ul class="speaker-card-talks">
        <li>
          <span class="talk-title">How Fully Homomorphic Encryption became (somehow) practical</span>
          <details class="abstract"><summary></summary>
            <div class="abstract-text">This talk provides an overview of the evolution of Fully Homomorphic Encryption (FHE), starting from the beginning and following the major ideas that transformed FHE from a theoretical breakthrough into a practical technology. We discuss the key innovations introduced over the years, including bootstrapping, modulus switching, key switching, and packing techniques, highlighting the challenges each was designed to address. The lecture concludes with a comparison of the main FHE families used today, discussing their strengths, limitations, and typical application scenarios.</div>
          </details>
        </li>
        <li>
          <span class="talk-title">Noise Growth and Parameter Selection in Fully Homomorphic Encryption</span>
          <details class="abstract"><summary></summary>
            <div class="abstract-text">Selecting cryptographic parameters is one of the central challenges in Fully Homomorphic Encryption. This lecture focuses on the relationship between parameters, security, correctness, and computational efficiency through the lens of noise analysis. We introduce the main sources of noise growth in homomorphic computations, explain how different operations affect the noise budget, and discuss how parameter choices determine the achievable computation depth. The lecture also illustrates the trade-offs involved in practical parameter selection and provides the intuition needed to analyze and optimize FHE circuits.</div>
          </details>
        </li>
      </ul>
    </div>
  </div>

  <div class="speaker-card">
    <img src="/images/speakers/leo.jpeg" alt="Leo Perrin">
    <div class="speaker-card-body">
      <div class="speaker-card-name"><a href="https://who.paris.inria.fr/Leo.Perrin/">Leo Perrin</a></div>
      <div class="speaker-card-affil">Inria — France</div>
      <ul class="speaker-card-talks">
        <li><span class="talk-title">The Cambrian Explosion of Symmetric Techniques for Advanced Protocols</span></li>
      </ul>
    </div>
  </div>

  <div class="speaker-card">
    <img src="/images/speakers/morten.webp" alt="Morten Øygarden">
    <div class="speaker-card-body">
      <div class="speaker-card-name"><a href="https://www.simula.no/people/morten.oygarden">Morten Øygarden</a></div>
      <div class="speaker-card-affil">University of Bergen / Simula Lab — Norway</div>
      <ul class="speaker-card-talks">
        <li><span class="talk-title">Algebraic Attacks on Arithmetization-Oriented Primitives</span></li>
      </ul>
    </div>
  </div>

  <div class="speaker-card">
    <img src="/images/speakers/markulf.png" alt="Markulf Kohlweiss">
    <div class="speaker-card-body">
      <div class="speaker-card-name"><a href="https://homepages.inf.ed.ac.uk/mkohlwei/">Markulf Kohlweiss</a></div>
      <div class="speaker-card-affil">University of Edinburgh — Scotland</div>
      <ul class="speaker-card-talks">
        <li><span class="talk-title">UC What You See: Brave New World of Zero-Overhead Pseudo-code UC</span></li>
      </ul>
    </div>
  </div>

</div>


### PROGRAM

<style>
.schedule { margin: 1.5em 0; }

.schedule-day {
  margin-bottom: 2.5em;
}

.day-header {
  font-size: 1.1em;
  font-weight: 700;
  letter-spacing: 0.04em;
  text-transform: uppercase;
  color: #333;
  border-bottom: 2px solid #ccc;
  padding-bottom: 0.3em;
  margin-bottom: 0.6em;
}

.schedule-row {
  display: flex;
  align-items: baseline;
  gap: 1.2em;
  padding: 0.45em 0;
  border-bottom: 1px solid #eee;
}

.schedule-row:last-child { border-bottom: none; }

.schedule-time {
  flex: 0 0 9em;
  font-size: 0.88em;
  color: #666;
  font-variant-numeric: tabular-nums;
  white-space: nowrap;
}

.schedule-event {
  flex: 1;
  font-size: 0.95em;
  color: #222;
}

.schedule-row.break .schedule-event,
.schedule-row.social .schedule-event {
  color: #888;
  font-style: italic;
}

.talk-title {
  font-style: italic;
  font-weight: 300;
  color: #111;
}

.talk-speaker {
  font-size: 0.88em;
  color: #555;
  margin-left: 0.3em;
}

details.abstract {
  display: inline;
}

details.abstract > summary {
  list-style: none;
  cursor: pointer;
  display: inline;
  font-size: 0.78em;
  font-style: normal;
  font-weight: normal;
  color: #0066cc;
  text-decoration: underline;
  margin-left: 0.6em;
}
details.abstract > summary::-webkit-details-marker { display: none; }
details.abstract > summary::marker { content: ""; }
details.abstract > summary::before { content: "Show abstract"; }
details.abstract[open] > summary::before { content: "Hide abstract"; }

details.abstract .abstract-text {
  display: block;
  margin-top: 0.5em;
  font-size: 0.88em;
  font-style: italic;
  font-weight: normal;
  color: #444;
  padding-left: 0.9em;
  border-left: 3px solid #ccc;
  line-height: 1.55;
}
</style>

<div class="schedule">

  <div class="schedule-day">
    <div class="day-header">Tuesday, 01.09</div>
    <div class="schedule-row break">
      <span class="schedule-time">14:00 – 14:30</span>
      <span class="schedule-event">Registration</span>
    </div>
    <div class="schedule-row break">
      <span class="schedule-time">14:30 – 14:45</span>
      <span class="schedule-event">Opening Remarks</span>
    </div>
    <div class="schedule-row">
      <span class="schedule-time">14:45 – 15:45</span>
      <span class="schedule-event">Alessio Caminata</span>
      <!-- <div class="schedule-event">
        <span class="talk-title">Solving polynomial systems with Gröbner bases</span>
        <span class="talk-speaker">(Alessio Caminata)</span>
        <details class="abstract"><summary></summary>
          <div class="abstract-text">Many problems arising in cryptography can be modeled by systems of multivariate polynomial equations over a finite field. It is therefore important to understand how to solve such systems efficiently. Gröbner bases provide a fundamental tool for this purpose.
In the first part of these lectures, we review and explain the connection between polynomial system solving and Gröbner bases, introducing important notions such as the Macaulay matrix. In the second part, we introduce the notions of solving degree, last fall degree, and degree of regularity, which are commonly used to study the complexity of polynomial systems arising in cryptography.</div>
        </details>
      </div> -->
    </div>
    <div class="schedule-row break">
      <span class="schedule-time">15:45 – 16:00</span>
      <span class="schedule-event">Short break</span>
    </div>
    <div class="schedule-row">
      <span class="schedule-time">16:00 – 17:00</span>
      <span class="schedule-event">Alessio Caminata</span>
      <!-- <div class="schedule-event">
        <span class="talk-title">How Fully Homomorphic Encryption became (somehow) practical</span>
        <span class="talk-speaker">(Chiara Marcolla)</span>
        <details class="abstract"><summary></summary>
          <div class="abstract-text">This talk provides an overview of the evolution of Fully Homomorphic Encryption (FHE), starting from the beginning and following the major ideas that transformed FHE from a theoretical breakthrough into a practical technology. We discuss the key innovations introduced over the years, including bootstrapping, modulus switching, key switching, and packing techniques, highlighting the challenges each was designed to address. The lecture concludes with a comparison of the main FHE families used today, discussing their strengths, limitations, and typical application scenarios.</div>
        </details>
      </div> -->
    </div>
    <div class="schedule-row social">
      <span class="schedule-time">17:00 – 18:00</span>
      <span class="schedule-event">Welcome Aperitif</span>
    </div>
  </div>

  <div class="schedule-day">
    <div class="day-header">Wednesday, 02.09</div>
    <div class="schedule-row">
      <span class="schedule-time">9:00 – 10:00</span>
      <span class="schedule-event">Leo Perrin</span>
      <!-- <div class="schedule-event">
        <span class="talk-title">Solving polynomial systems with Gröbner bases</span>
        <span class="talk-speaker">(Alessio Caminata)</span>
        <details class="abstract"><summary></summary>
          <div class="abstract-text">Many problems arising in cryptography can be modeled by systems of multivariate polynomial equations over a finite field. It is therefore important to understand how to solve such systems efficiently. Gröbner bases provide a fundamental tool for this purpose.
In the first part of these lectures, we review and explain the connection between polynomial system solving and Gröbner bases, introducing important notions such as the Macaulay matrix. In the second part, we introduce the notions of solving degree, last fall degree, and degree of regularity, which are commonly used to study the complexity of polynomial systems arising in cryptography.</div>
        </details>
      </div> -->
    </div>
    <div class="schedule-row">
      <span class="schedule-time">10:00 – 11:00</span>
      <span class="schedule-event">Leo Perrin</span>
      <!-- <div class="schedule-event">
        <span class="talk-title">Noise Growth and Parameter Selection in Fully Homomorphic Encryption</span>
        <span class="talk-speaker">(Chiara Marcolla)</span>
        <details class="abstract"><summary></summary>
          <div class="abstract-text">Selecting cryptographic parameters is one of the central challenges in Fully Homomorphic Encryption. This lecture focuses on the relationship between parameters, security, correctness, and computational efficiency through the lens of noise analysis. We introduce the main sources of noise growth in homomorphic computations, explain how different operations affect the noise budget, and discuss how parameter choices determine the achievable computation depth. The lecture also illustrates the trade-offs involved in practical parameter selection and provides the intuition needed to analyze and optimize FHE circuits.</div>
        </details>
      </div> -->
    </div>
    <div class="schedule-row break">
      <span class="schedule-time">11:00 – 11:30</span>
      <span class="schedule-event">Coffee Break</span>
    </div>
    <div class="schedule-row">
      <span class="schedule-time">11:30 – 12:30</span>
      <span class="schedule-event">Morten Øygarden</span>
    </div>
    <div class="schedule-row break">
      <span class="schedule-time">12:30 – 14:00</span>
      <span class="schedule-event">Lunch Break</span>
    </div>
    <div class="schedule-row">
      <span class="schedule-time">14:00 – 15:00</span>
      <span class="schedule-event">Morten Øygarden</span>
    </div>
    <div class="schedule-row">
      <span class="schedule-time">15:00 – 16:00</span>
      <span class="schedule-event">Chiara Marcolla</span>
    </div>
    <div class="schedule-row break">
      <span class="schedule-time">16:00 – 16:30</span>
      <span class="schedule-event">Coffee Break</span>
    </div>
    <div class="schedule-row">
      <span class="schedule-time">16:30 – 17:30</span>
      <span class="schedule-event">Discussion</span>
    </div>
  </div>

  <div class="schedule-day">
    <div class="day-header">Thursday, 03.09</div>
    <div class="schedule-row">
      <span class="schedule-time">9:00 – 10:00</span>
      <span class="schedule-event">Chiara Marcolla</span>
    </div>
    <div class="schedule-row">
      <span class="schedule-time">10:00 – 11:00</span>
      <span class="schedule-event">Markulf Kohlweiss</span>
    </div>
    <div class="schedule-row break">
      <span class="schedule-time">11:00 – 11:30</span>
      <span class="schedule-event">Coffee Break</span>
    </div>
    <div class="schedule-row">
      <span class="schedule-time">11:30 – 12:30</span>
      <span class="schedule-event">Markulf Kohlweiss</span>
    </div>
    <div class="schedule-row break">
      <span class="schedule-time">12:30 – 14:00</span>
      <span class="schedule-event">Lunch Break</span>
    </div>
    <div class="schedule-row">
      <span class="schedule-time">14:00 – 15:00</span>
      <span class="schedule-event">Student Presentations</span>
    </div>
    <div class="schedule-row">
      <span class="schedule-time">15:00 – 16:00</span>
      <span class="schedule-event">Student Presentations</span>
    </div>
  </div>

</div>



 





