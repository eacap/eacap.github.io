---
title: Contact
---

For any inquiries, please contact us at [eagcap@gmail.com](mailto:eagcap@gmail.com).

<style>
.prose h2.organizers-heading {
  position: relative;
  display: table;
  isolation: isolate;

  font-family: var(--sans);
  font-size: 30px;
  font-weight: 600;
  letter-spacing: -0.025em;
  line-height: 1.2;
  color: var(--foreground);

  background: none;
  padding: 0 5px 2px 2px;
  margin-bottom: 24px;
}

/* Curved highlighter */
.organizers-highlight {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  z-index: 0;
  overflow: visible;
  pointer-events: none;
}

.organizers-heading > span {
  position: relative;
  z-index: 1;
}


  .organizer-grid {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 18px;
    margin-top: 20px;
  }

  .organizer-card {
    padding: 24px;
    border: 1px solid #d8e0d6;
    border-radius: 12px;
  }

  .organizer-card h3 {
    margin: 0 0 8px;
  }

  .organizer-card h3 a {
    color: inherit;
    text-decoration: none;
  }

  .organizer-card h3 a:hover {
    text-decoration: underline;
    text-underline-offset: 3px;
  }

  .organizer-card p {
    margin: 0;
    opacity: 0.75;
  }

.organizer-profile {
  display: block;
  margin-top: 18px;
  font-size: 0.85rem;
  font-weight: 500;
  color: #416c4f;
  text-decoration: none !important;
  width: fit-content;
  margin: 8px 0 0 auto;
}

.organizer-profile:hover {
  text-decoration: underline !important;
  text-underline-offset: 4px;
}
  @media (max-width: 600px) {
    .organizer-grid {
      grid-template-columns: 1fr;
    }
  }
</style>

<h2 class="organizers-heading">
  <svg class="organizers-highlight"
       viewBox="0 0 300 70"
       preserveAspectRatio="none"
       aria-hidden="true">
    <path
      d="M 65 60 C 140 56, 218 48, 282 50"
      fill="none"
      stroke="#dce9de"
      stroke-width="28"
      stroke-linecap="round"
    />
  </svg>
  <span>Organizers</span>
</h2>

<div class="organizer-grid">

  <div class="organizer-card">
    <h3>
      <a href="https://sites.google.com/view/arata-matsuda"
         target="_blank" rel="noopener noreferrer">
        Arata Matsuda
      </a>
    </h3>
    <p>University of Oxford; Hokkaido University</p>
    <a href="https://sites.google.com/view/arata-matsuda"
   class="organizer-profile" target="_blank" rel="noopener noreferrer">
  View Profile ↗
</a>
  </div>

  <div class="organizer-card">
    <h3>
      <a href="https://philpeople.org/profiles/hyejoon-an"
         target="_blank" rel="noopener noreferrer">
        Hyejoon An
      </a>
    </h3>
    <p>Seoul National University</p>
    <a href="https://philpeople.org/profiles/hyejoon-an"
   class="organizer-profile" target="_blank" rel="noopener noreferrer">
  View Profile ↗
</a>
  </div>

 </div>
