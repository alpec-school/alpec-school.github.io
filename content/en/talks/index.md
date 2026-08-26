---
title: "Participant Presentations"
featured_image: "/images/backgrounds/_ALE1907.jpg"
position_vertical: 35%
menu:
  main:
    weight: 7
---


<style>
.talk-list {
  display: flex;
  flex-direction: column;
  gap: 1.4em;
  margin: 1.5em 0 2.5em;
}

.talk-entry {
  padding-bottom: 1.2em;
  border-bottom: 1px solid #eee;
}

.talk-entry:last-child {
  border-bottom: none;
  padding-bottom: 0;
}

.talk-entry-name {
  font-size: 0.97em;
  font-weight: 700;
  color: #0066cc;
  margin-bottom: 0.15em;
}

.talk-entry-affil {
  font-size: 0.78em;
  color: #666;
  margin-bottom: 0.5em;
  line-height: 1.35;
}

.talk-entry .talk-title {
  display: block;
  font-size: 0.92em;
  font-style: italic;
  font-weight: 600;
  color: #111;
}

.talk-entry details.abstract {
  display: block;
  margin-top: 0.25em;
}

.talk-entry details.abstract > summary {
  list-style: none;
  cursor: pointer;
  display: inline;
  font-size: 0.8em;
  font-style: normal;
  font-weight: normal;
  color: #0066cc;
  text-decoration: underline;
}
.talk-entry details.abstract > summary::-webkit-details-marker { display: none; }
.talk-entry details.abstract > summary::marker { content: ""; }
.talk-entry details.abstract > summary::before { content: "Show abstract"; }
.talk-entry details.abstract[open] > summary::before { content: "Hide abstract"; }

.talk-entry details.abstract .abstract-text {
  display: block;
  margin-top: 0.4em;
  font-size: 0.85em;
  font-style: italic;
  font-weight: normal;
  color: #444;
  padding-left: 0.7em;
  border-left: 3px solid #ccc;
  line-height: 1.55;
}

.talk-entry details.abstract .talk-ref {
  display: block;
  margin-top: 0.45em;
  font-size: 0.78em;
  font-style: normal;
  color: #666;
  padding-left: 0.7em;
  line-height: 1.45;
}

.talk-entry details.abstract .talk-ref a {
  color: #0066cc;
}
</style>

### Participant Presentations


<div class="talk-list">

  <div class="talk-entry">
    <div class="talk-entry-name">Asmaa Cherkaoui</div>
    <div class="talk-entry-affil">Faculty of Sciences Ain Chock, University Hassan II of Casablanca — Morocco</div>
    <span class="talk-title">Syndrome-Based Hashing over F<sub>p</sub></span>
    <details class="abstract"><summary></summary>
      <div class="abstract-text">We introduce an FSB-inspired hash construction over F<sub>p</sub> based on an alphabet encoding that assigns both a position and a nonzero field coefficient to each message symbol. This produces a structured sparse representation that is compressed through a public matrix over F<sub>p</sub>. We present the main design principles and the current stage of its analysis.</div>
    </details>
  </div>

  <div class="talk-entry">
    <div class="talk-entry-name">Luca Di Domenico</div>
    <span class="talk-title">Performant Primality Test on a Pell's Cubic</span>
    <details class="abstract"><summary></summary>
      <div class="abstract-text">Primality testing is an especially useful topic for public-key cryptography. Thanks to carefully constructed necessary primality conditions, a primality test algorithm based on Pell's cubic can be defined. This test has complexity O(log(n)) and it is deterministic below 2^36.</div>
      <div class="talk-ref">Featured in the speaker's Master's thesis (Università di Trento, 2024) and in a published article: <a href="https://doi.org/10.1007/s00009-025-02839-w">doi.org/10.1007/s00009-025-02839-w</a>.</div>
    </details>
  </div>

  <div class="talk-entry">
    <div class="talk-entry-name">Leonardo Errati</div>
    <div class="talk-entry-affil">Politecnico di Torino — Italy</div>
    <span class="talk-title">Canonical Lifting for Group-Action Protocols: Beyond Ring Signatures?</span>
    <details class="abstract"><summary></summary>
      <div class="abstract-text">Canonical liftings were developed to compress group-action-based sigma protocols by replacing a full witness with a compact representative. Under some hypotheses, they seem to preserve the underlying hardness of group-action problems. This abstraction was used to produce a (linkable) ring signature, CE(Le)ReS. Can it be used to construct other primitives, such as blind signatures (e.g., Tanuki, LEAF)? Can they have other roles, as cryptographic primitives? What happens if we instantiate them on, e.g., the group actions underlying lattices and isogenies?</div>
      <div class="talk-ref">The idea started with our recent work<a href="https://eprint.iacr.org/2026/1348">eprint.iacr.org/2026/1348</a>.</div>
    </details>
  </div>

  <div class="talk-entry">
    <div class="talk-entry-name">Massimo Fumiani</div>
    <div class="talk-entry-affil">University of Innsbruck — Austria</div>
    <span class="talk-title">Algebraic Cryptanalysis of Bounded-Error LWE</span>
    <details class="abstract"><summary></summary>
      <div class="abstract-text">We study the Learning With Errors problem in the bounded-error setting from an algebraic perspective. We present a new algorithm, that solves the resulting polynomial system arising from bounded-error LWE instances. In contrast to previous approaches, whose cost estimates rely on heuristic assumptions such as the degree of regularity or semi-regularity of the system, our analysis yields a precise and provable complexity bound. This provides a more reliable assessment of the algebraic hardness of bounded-error LWE and of the security margins of schemes based on it.</div>
    </details>
  </div>

  <div class="talk-entry">
    <div class="talk-entry-name">Abdelkarim Lkoaiza</div>
    <div class="talk-entry-affil">Laboratory of Mathematical Analysis, Algebra and Applications (LAM2A), Faculty of Sciences Ain Chock (FSAC), University Hassan II of Casablanca — Morocco</div>
    <span class="talk-title">An Extended Grendel Approach Applied to Blockchain Signature as an Alternative to Keccak Permutation</span>
    <details class="abstract"><summary></summary>
      <div class="abstract-text">This work introduces a sponge-based hash function using the Grendel permutation as an alternative to Keccak for blockchain signatures. It extends the Legendre symbol and Euler's criterion from prime fields to invertible elements of Z/pqZ and provides an implementation without predefined hashing libraries, together with a security analysis.</div>
    </details>
  </div>

  <div class="talk-entry">
    <div class="talk-entry-name">Carmine Mirra</div>
    <div class="talk-entry-affil">Università degli Studi della Campania "Luigi Vanvitelli" — Italy</div>
    <span class="talk-title">A Functional Encryption scheme from a group-based version of the Learning With Errors problem</span>
    <details class="abstract"><summary></summary>
      <div class="abstract-text">We explore the Learning Homomorphism with Noise problem, a group-theoretic formulation of Learning With Errors, one of the hardness assumptions in post-quantum cryptography. We present a generalization inspired by TFHE, a fully homomorphic encryption scheme over the real torus. Finally, we describe an application to functional encryption for inner product. This is joint work with D. Kahrobaei, A. Tortora and M. Tota.</div>
    </details>
  </div>

  <div class="talk-entry">
    <div class="talk-entry-name">Florias Papadopoulos</div>
    <div class="talk-entry-affil">University of St. Gallen — Switzerland</div>
    <span class="talk-title">Privacy-preserving Proximity Testing from Geometric Fuzzy Matching</span>
    <details class="abstract"><summary></summary>
      <div class="abstract-text">Privacy-preserving proximity testing allows users to determine whether two parties are sufficiently close, without revealing their exact locations. We introduce Geometric Fuzzy Matching (GFM), which generalizes this idea to arbitrary geometric regions. GFM supports both distance-based proximity and complex regions, while keeping both locations private.</div>
      <div class="talk-ref">Based on joint work with Ioannis Katis and Katerina Mitrokotsa, published at <a href="https://dl.acm.org/doi/10.1145/3779208.3785374">ACM AsiaCCS 2026</a>.</div>
    </details>
  </div>

  <div class="talk-entry">
    <div class="talk-entry-name">Sundas Tariq</div>
    <div class="talk-entry-affil">3MI Labs and COSIC, KU Leuven — Belgium</div>
    <span class="talk-title">Experimental Evaluation of Dickson Polynomials as an S-Box for Algebraic Hash Functions</span>
    <details class="abstract"><summary></summary>
      <div class="abstract-text">We evaluate Dickson polynomials as replacements for monomial S-boxes in a STARK-friendly hash function, leveraging their dense algebraic structure and lack of the multiplicative homomorphic property. Unexpectedly, experimental results show that the solving degree of the resulting polynomial system remains unchanged, despite an increase in time and memory overhead.</div>
    </details>
  </div>

  <div class="talk-entry">
    <div class="talk-entry-name">Simone Trebiani</div>
    <div class="talk-entry-affil">Université de Neuchâtel — Switzerland</div>
    <span class="talk-title">Symmetric Models for Syndrome Decoding</span>
    <details class="abstract"><summary></summary>
      <div class="abstract-text">We introduce a new model, based on elementary symmetric polynomials, that can be used to solve the exact variant of the Syndrome Decoding Problem in the binary case. We provide an estimate of its computational complexity by showing bounds on the degree of regularity of the ideal associated with the model. Based on joint work with Elisa Gorla.</div>
    </details>
  </div>

  <div class="talk-entry">
    <div class="talk-entry-name">Stefano Trevisani</div>
    <div class="talk-entry-affil">TU Wien — Austria</div>
    <span class="talk-title">Boosting Efficiency and Security in Arithmetization-Oriented Hashing for Zero-Knowledge Proof Systems</span>
    <details class="abstract"><summary></summary>
      <div class="abstract-text">Arithmetization-oriented (AO) compression functions are a core component of the Merkle tree commitment schemes used in modern ZK-SNARK frameworks. In this talk, we will look at the recently introduced PAX family of AO compression modes, that allow to instantiate a compression function from an underlying cryptographic permutation. The PAX family unifies and generalizes the description of popular approaches in the literature, namely the single-iteration sponge, and the so-called Jive and Trunc modes. In particular, unlike the single-iteration sponge, PAX allows to achieve optimal collision and preimage resistance, allowing a more efficient instantiation in settings, such as Merkle Trees, where Random-Oracle indifferentiability is typically not necessary.</div>
    </details>
  </div>

</div>


