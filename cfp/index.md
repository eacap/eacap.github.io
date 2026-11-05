---
layout: page
eyebrow: "EACAP 2027"
title: Call for Papers
---
<div class="cfp-conference-info">
  <div class="cfp-conference-item">
    <div class="cfp-conference-label">
      <svg viewBox="0 0 24 24" fill="none"
           stroke="currentColor" stroke-width="1.8"
           stroke-linecap="round" stroke-linejoin="round"
           aria-hidden="true">
        <rect x="3" y="5" width="18" height="16" rx="2"/>
        <path d="M16 3v4M8 3v4M3 10h18"/>
        <circle cx="8" cy="13.5" r="0.65" fill="currentColor" stroke="none"/>
        <circle cx="12" cy="13.5" r="0.65" fill="currentColor" stroke="none"/>
        <circle cx="16" cy="13.5" r="0.65" fill="currentColor" stroke="none"/>
        <circle cx="8" cy="17" r="0.65" fill="currentColor" stroke="none"/>
        <circle cx="12" cy="17" r="0.65" fill="currentColor" stroke="none"/>
        <circle cx="16" cy="17" r="0.65" fill="currentColor" stroke="none"/>
      </svg>
      <span>Conference Dates</span>
    </div>
    <div class="cfp-conference-value">
      June 16–18, 2027
    </div>
  </div>

  <div class="cfp-conference-item">
    <div class="cfp-conference-label">
      <svg viewBox="0 0 24 24" fill="none"
           stroke="currentColor" stroke-width="1.8"
           stroke-linecap="round" stroke-linejoin="round"
           aria-hidden="true">
        <path d="M20 10c0 5-8 11-8 11S4 15 4 10a8 8 0 1 1 16 0Z"/>
        <circle cx="12" cy="10" r="2.5"/>
      </svg>
      <span>Venue</span>
    </div>
    <div class="cfp-conference-value">
      Seoul National University, South Korea
    </div>
  </div>
</div>

<p class="cfp-intro">
  We are pleased to announce the inaugural East Asian
  Graduate Conference in Analytic Philosophy (EACAP),
  to be held in Seoul in June 2027. EACAP welcomes
  submissions from current graduate students in all
  areas of analytic philosophy, broadly construed.
</p>

<p class="cfp-intro">
  We aim to provide on-campus accommodation for accepted presenters where needed during the conference.
</p>

<style>
.cfp-intro {
  width: 750px;
  max-width: none;
  text-align: justify;
  text-wrap: normal;
}

/* Conference dates and venue */
.cfp-conference-info {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 28px;
  padding-bottom: 18px;
  margin: 0 0 30px;
  border-bottom: 1px solid var(--border);
}

.cfp-conference-label {
  display: flex;
  align-items: center;
  gap: 8px;
  margin-bottom: 5px;
  font-family: var(--sans);
  font-size: 12px;
  font-weight: 500;
  letter-spacing: 0.025em;
  text-transform: uppercase;
  color: var(--accent);
}

.cfp-conference-label svg {
  width: 16px;
  height: 16px;
  color: var(--accent);
  flex-shrink: 0;
}

.cfp-conference-value {
  font-family: var(--sans);
  font-size: 16px;
  font-weight: 400;
  line-height: 1.5;
  color: var(--foreground);
}

@media (max-width: 750px) {
  .cfp-conference-info {
    grid-template-columns: 1fr;
    gap: 16px;
    padding-bottom: 16px;
    margin-bottom: 24px;
  }

  .cfp-conference-label {
    margin-bottom: 4px;
  }

  .cfp-conference-value {
    font-size: 15px;
  }
}

  .eacap-dates {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 20px;
    margin: 28px 0 36px;
  }

  .eacap-date-card {
    display: flex;
    align-items: center;
    gap: 18px;
    padding: 16px 20px;
    border: 1px solid #c3d4c7;
    border-radius: 12px;
  }

  .eacap-date-icon {
    width: 25px;
    height: 25px;
    flex-shrink: 0;
    color: #416c4f;
  }

  .eacap-date-text {
    min-width: 0;
    padding-left: 18px;
    border-left: 1px solid #c3d4c7;
  }

  .eacap-date-label {
    display: block;
    margin-bottom: 5px;
    font-size: 0.7rem;
    font-weight: 700;
    letter-spacing: 0.07em;
    color: #416c4f;
  }

  .eacap-date-value {
    display: block;
    font-family: Georgia, serif;
    font-size: clamp(0.95rem, 1.4vw, 1.25rem);
    font-weight: 600;
    line-height: 1.3;
    white-space: nowrap;
  }

  @media (max-width: 750px) {
    .eacap-dates {
      grid-template-columns: 1fr;
      gap: 12px;
    }
  }
  .section-heading {
  display: flex;
  align-items: center;
  gap: 28px;
  width: min(1068px, calc(100vw - 40px));
  font-size: 2.25rem;
  margin-top: 48px;
}

.section-heading::after {
  content: "";
  flex: 1;
  height: 1px;
  transform: translateY(3px);
  background: #cfd8cf;
}

.cfp-format {
  padding: 8px 0;
}

.cfp-format + .cfp-format {
  border-top: 1px solid #d6ddd4;
  margin-top: 8px;
  padding-top: 18px;
}

.cfp-format h3 {
  display: flex;
  align-items: baseline;
  gap: 20px;
  margin: 0 0 12px;
  font-family: Georgia, serif;
  font-size: 1.7rem;
  font-weight: 600;
}

.cfp-format-number {
  font-family: sans-serif;
  font-size: 0.85rem;
  font-weight: 600;
  color: #416c4f;
}

.cfp-format p {
  margin: 0 0 12px;
}

.cfp-format p:last-child {
  margin-bottom: 0;
}

#guidelines-heading + ul {
  width: min(1068px, calc(100vw - 40px));
  max-width: none;
}

/* Paper Presentations & WIP Forums */
.cfp-format p {
  text-align: justify;
  text-justify: inter-word;
}

/* Submission Guidelines */
#guidelines-heading + ul li {
  text-align: justify;
  text-justify: inter-word;
}


@media (max-width: 750px) {

  /* CFP introduction */
  .cfp-intro {
    width: 100% !important;
    max-width: 100% !important;
    box-sizing: border-box;
    text-align: left !important;
    text-wrap: normal;
  }

  /* Section headings and horizontal lines */
  .section-heading {
    width: 100% !important;
    font-size: 1.8rem;
    gap: 16px;
  }

  /* Submission formats */
  .cfp-format p {
    text-align: left !important;
  }

  /* Submission guidelines */
  #guidelines-heading + ul {
    width: 100% !important;
    max-width: 100% !important;
    box-sizing: border-box;
  }

  #guidelines-heading + ul li {
    text-align: left !important;
  }

  /* Prevent date text from overflowing */
  .eacap-date-value {
    white-space: normal;
  }

}

.cfp-submit,
.cfp-submit:hover,
.cfp-submit:focus {
  color: #fff !important;
  text-decoration: none !important;
  font-size: 1.05rem !important;
  padding: 13px 22px !important;
}
 
.cfp-submit-row {
  display: flex;
  justify-content: flex-end;
  width: min(1068px, calc(100vw - 40px));
  margin-top: 24px;
}

@media (max-width: 750px) {
  .cfp-submit-row {
    width: 100%;
  }
}


/* Keynote Speakers */
.cfp-keynote-card {
  max-width: 760px;
  margin: 30px 0 34px;
  padding: 0;
}

/* Heading */
.prose .cfp-keynote-card h2.cfp-keynote-heading {
  position: relative;
  display: table;
  isolation: isolate;
  width: auto;
  margin: 0 0 14px;
  padding: 0 4px 2px;
  font-family: var(--sans);
  font-size: 21px;
  font-weight: 600;
  letter-spacing: -0.02em;
  line-height: 1.3;
  color: var(--foreground);
}

/* Rectangular highlight */
.cfp-keynote-heading::after {
  content: "";
  position: absolute;
  left: 9%;
  right: 0;
  bottom: 2px;
  height: 15px;
  background: #dce9de;
  border-radius: 2px;
  transform: rotate(-1deg);
  z-index: -1;
  pointer-events: none;
}

/* Speaker list */
.cfp-keynote-list {
  margin: 0;
  padding-left: 22px;
}

.prose .cfp-keynote-list li {
  margin: 0 0 3px;
  font-family: var(--sans);
  font-size: 16px;
  line-height: 1.8;
  color: var(--foreground);
}

.cfp-keynote-list strong {
  font-weight: 600;
}

/* Announcement note */
.prose .cfp-keynote-note {
  display: flex;
  align-items: center;
  gap: 8px;
  margin: 12px 0 0;
  font-family: var(--sans);
  font-size: 12px;
  font-weight: 400;
  line-height: 1.5;
  color: var(--muted);
}

.cfp-keynote-note svg {
  width: 15px;
  height: 15px;
  flex-shrink: 0;
}

/* Mobile */
@media (max-width: 750px) {
  .prose .cfp-keynote-card h2.cfp-keynote-heading {
    font-size: 19px;
  }
}
</style>


<div class="cfp-keynote-card">
  <h2 class="cfp-keynote-heading">Keynote Speakers</h2>

  <ul class="cfp-keynote-list">
    <li><strong>Matthew Mandelkern</strong> (New York University)</li>
    <li><strong>Kengo Miyazono</strong> (Hokkaido University)</li>
  </ul>

  <div class="cfp-keynote-note">
    <svg viewBox="0 0 24 24"
         fill="none"
         stroke="currentColor"
         stroke-width="1.7"
         stroke-linecap="round"
         stroke-linejoin="round"
         aria-hidden="true">
      <circle cx="12" cy="12" r="9"/>
      <path d="M12 11v5"/>
      <path d="M12 8h.01"/>
    </svg>
    <span>Further announcements to follow.</span>
  </div>
</div>

<div class="eacap-dates">
  <div class="eacap-date-card">
    <!-- Calendar icon + timezone -->
    <div style="position: relative; display: flex; align-items: center; justify-content: center; flex-shrink: 0;">
      <svg class="eacap-date-icon" viewBox="0 0 24 24"
           fill="none" stroke="currentColor" stroke-width="1.7"
           stroke-linecap="round" stroke-linejoin="round"
           aria-hidden="true">
        <rect x="3" y="5" width="18" height="16" rx="2"/>
        <path d="M16 3v4M8 3v4M3 10h18"/>
      </svg>

      <span style="
        position: absolute;
        top: calc(100% + 5px);
        left: 50%;
        transform: translateX(-50%);
        font-family: var(--sans);
        font-size: 9px;
        font-weight: 400;
        line-height: 1;
        color: var(--muted);
        white-space: nowrap;
      ">UTC+09:00</span>
    </div>

    <div class="eacap-date-text">
      <span class="eacap-date-label">SUBMISSION DEADLINE</span>
      <span class="eacap-date-value">February 20, 2027</span>
    </div>
  </div>

  <div class="eacap-date-card">
    <!-- Mail icon -->
    <svg class="eacap-date-icon" viewBox="0 0 24 24"
         fill="none" stroke="currentColor" stroke-width="1.7"
         stroke-linecap="round" stroke-linejoin="round"
         aria-hidden="true">
      <rect x="2" y="4" width="20" height="16" rx="2"/>
      <path d="m2 6 10 7 10-7"/>
    </svg>

    <div class="eacap-date-text">
      <span class="eacap-date-label">AUTHORS NOTIFIED BY</span>
      <span class="eacap-date-value">April 10, 2027</span>
    </div>
  </div>
</div>

<h2 class="section-heading">Submission Formats</h2>

<p>
  We invite submissions in two categories:
</p>

<div class="cfp-format">
  <h3>
    <span class="cfp-format-number">01</span>
    Paper Presentations
  </h3>

  <p>
   Paper Presentations are allotted 50 minutes each, 
   including 25–30 minutes for the presentation, 
   followed by Q&A.
  </p>

  <p>
    Submissions must consist of a paper of no more than
    <strong>3,000 words</strong>
    (exclusive of footnotes and bibliography).
  </p>
</div>

<div class="cfp-format">
  <h3>
    <span class="cfp-format-number">02</span>
    WIP Forums
  </h3>

  <p>
    EACAP 2027 will also feature WIP Forums to encourage
    the exchange of ideas and constructive feedback on
    research in progress. Each forum consists of four
    10-minute presentations, followed by a 40-minute
    coffee break during which presenters and participants
    can freely discuss the presented work.
  </p>

  <p>
     Submissions must consist of an extended abstract of no more than
    <strong>500 words</strong>
    (exclusive of footnotes and bibliography).
  </p>
</div>

<h2 class="section-heading" id="guidelines-heading">Submission Guidelines</h2>

- All submissions must be in PDF format and prepared for **anonymous review**. Please ensure that neither the file name nor the document itself contains any identifying information, including the author's name or institutional affiliation.
- All submissions must be accompanied by an abstract of approximately 150 words, to be entered in the designated field on the submission form.
- Work published by the submission deadline will not be considered.
- Only one submission per author is permitted. However, authors submitting to the Paper Presentation may indicate whether they would like their papers to be considered for the WIP Forum if not selected for a Paper Presentation. This option will appear when selecting 'Paper Presentation' on the submission form.
- All submissions should be made through the online submission form linked below. If you experience difficulties accessing the form or submitting your work, please contact us at
  <a href="mailto:eagcap@gmail.com">eagcap@gmail.com</a>.

<div class="cfp-submit-row">
  <a href="{{ '/2027/submission/' | relative_url }}"
     class="btn btn-primary cfp-submit">
    Submit a Paper <span aria-hidden="true">→</span>
  </a>
</div>
