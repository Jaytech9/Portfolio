.about-text {
  max-width: 750px;            /* keeps text column at readable width */
  margin: 0 auto;              /* centers the block */
  padding: 20px;
  font-size: 1.1rem;           /* clean, slightly larger than body */
  line-height: 1.8;            /* breathing space between lines */
  color: var(--text-primary);  /* adapts to light/dark theme */
  text-align: justify;         /* clean alignment */
}

/* Paragraph spacing */
.about-text p {
  margin-bottom: 1.5rem;
  color: var(--text-secondary);  /* softer than headings */
}

/* Strong emphasis */
.about-text strong {
  font-weight: 600;
  color: var(--text-primary);    /* keeps emphasis visible in both modes */
}



.about-text {
    font-size: 1.1rem;
    line-height: 1.8;              /* Extra line spacing for readability */
    color: var(--text-secondary);
}

.about-text p {
    margin-bottom: 1.5rem;
}

.nav-container {
    display: flex;
    justify-content: space-between;   /* Logo on left, menu on right */
    align-items: center;
    padding: 1rem 0;
}