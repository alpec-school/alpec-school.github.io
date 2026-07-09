---
title: "Program"
featured_image: "/images/backgrounds/_ALE1907.jpg"
position_vertical: 35%
menu:
  main:
    weight: 1
---
This is a tentative outline of the program. Further details will come soon.



### SPEAKERS
- <span style="color:blue">[Alessio Caminata](https://alessiocaminata.wixsite.com/alca) (University of Genoa - Italy)</span> 
- <span style="color:blue">[Chiara Marcolla](https://scholar.google.com/citations?user=QuN8bAwAAAAJ&hl=it) (TII - Abu Dhabi UAE)</span>
- <span style="color:blue">[Leo Perrin](https://who.paris.inria.fr/Leo.Perrin/) (Inria - France)</span>
- <span style="color:blue">[Morten Øygarden](https://www.simula.no/people/morten.oygarden) (University of Bergen - Norway)</span>
- <span style="color:blue">[Markulf Kohlweiss](https://homepages.inf.ed.ac.uk/mkohlwei/) (University of Edinburgh - Scotland)</span>

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
  font-weight: 600;
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

<p>Tentative program</p>

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
      <span class="schedule-event">(Talk)</span>
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
      <span class="schedule-event">(Talk)</span>
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
      <span class="schedule-event">(Talk)</span>
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
      <span class="schedule-event">(Talk)</span>
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
      <span class="schedule-event">(Talk)</span>
    </div>
    <div class="schedule-row break">
      <span class="schedule-time">12:30 – 14:00</span>
      <span class="schedule-event">Lunch Break</span>
    </div>
    <div class="schedule-row">
      <span class="schedule-time">14:00 – 15:00</span>
      <span class="schedule-event">(Talk)</span>
    </div>
    <div class="schedule-row">
      <span class="schedule-time">15:00 – 16:00</span>
      <span class="schedule-event">(Talk)</span>
    </div>
    <div class="schedule-row break">
      <span class="schedule-time">16:00 – 16:30</span>
      <span class="schedule-event">Coffee Break</span>
    </div>
    <div class="schedule-row">
      <span class="schedule-time">16:30 – 17:00</span>
      <span class="schedule-event">(Discussion)</span>
    </div>
  </div>

  <div class="schedule-day">
    <div class="day-header">Thursday, 03.09</div>
    <div class="schedule-row">
      <span class="schedule-time">9:00 – 10:00</span>
      <span class="schedule-event">(Talk)</span>
    </div>
    <div class="schedule-row">
      <span class="schedule-time">10:00 – 11:00</span>
      <span class="schedule-event">(Talk)</span>
    </div>
    <div class="schedule-row break">
      <span class="schedule-time">11:00 – 11:30</span>
      <span class="schedule-event">Coffee Break</span>
    </div>
    <div class="schedule-row">
      <span class="schedule-time">11:30 – 12:30</span>
      <span class="schedule-event">(Talk)</span>
    </div>
    <div class="schedule-row break">
      <span class="schedule-time">12:30 – 14:00</span>
      <span class="schedule-event">Lunch Break</span>
    </div>
    <div class="schedule-row">
      <span class="schedule-time">14:00 – 15:00</span>
      <span class="schedule-event">(Talk)</span>
    </div>
    <div class="schedule-row">
      <span class="schedule-time">15:00 – 16:00</span>
      <span class="schedule-event">(Discussion)</span>
    </div>
  </div>

</div>



 





