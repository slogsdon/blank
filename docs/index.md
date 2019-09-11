---
title: blank.css
layout: default
---

# `blank.css`

## Examples

- General
  - [Headings](#headings)
  - [Buttons](#buttons)
  - [Inputs](#inputs)
  - [Colors](#colors)
- Layouts
  - [Stack](#layout-stack)
  - [One-Two-One](#layout-one-two-one)
  - [One-Two-One-Responsive](#layout-one-two-one-responsive)

### General

<fieldset id="headings">
  <legend>Headings</legend>

  <h1>Heading 1</h1>
  <h2>Heading 2</h2>
  <h3>Heading 3</h3>
  <h4>Heading 4</h4>
  <h5>Heading 5</h5>
  <h6>Heading 6</h6>
</fieldset>

<fieldset id="buttons">
  <legend>Buttons</legend>

  <button type="submit">Primary</button>
  <button type="button">Secondary</button>

  <p><code>:disabled</code></p>

  <button type="submit" disabled>Primary</button>
  <button type="button" disabled>Secondary</button>
</fieldset>

<fieldset id="inputs">
  <legend>Inputs</legend>

  <input type="text" placeholder="type here">
  <input type="text" placeholder="type here" value="entered text">
  <label><input type="checkbox"> Checkbox</label>
  <label><input type="radio"> Radio</label>

  <p><code>:disabled</code></p>

  <input type="text" placeholder="type here" disabled>
  <input type="text" placeholder="type here" value="entered text" disabled>
  <label><input type="checkbox" disabled> Checkbox</label>
  <label><input type="radio" disabled> Radio</label>
</fieldset>

<fieldset id="colors" class="colors">
  <legend>Colors</legend>

  <div style="display:inline-block;width: 45%">
    <span style="color: black">black</span><br>
    <span style="color: var(--grey-0)">grey-0</span><br>
    <span style="color: var(--grey-1)">grey-1</span><br>
    <span style="color: var(--grey-2)">grey-2</span><br>
    <span style="color: var(--grey-3)">grey-3</span><br>
    <span style="color: var(--grey-4)">grey-4</span><br>
    <span style="color: var(--grey-5)">grey-5</span><br>
    <span style="color: var(--grey-6)">grey-6</span><br>
    <span style="color: var(--grey-7)">grey-7</span><br>
    <span style="color: white">white</span>
  </div>

  <div style="background: black;display:inline-block;width: 45%">
    <span style="color: black">black</span><br>
    <span style="color: var(--grey-0)">grey-0</span><br>
    <span style="color: var(--grey-1)">grey-1</span><br>
    <span style="color: var(--grey-2)">grey-2</span><br>
    <span style="color: var(--grey-3)">grey-3</span><br>
    <span style="color: var(--grey-4)">grey-4</span><br>
    <span style="color: var(--grey-5)">grey-5</span><br>
    <span style="color: var(--grey-6)">grey-6</span><br>
    <span style="color: var(--grey-7)">grey-7</span><br>
    <span style="color: white">white</span>
  </div>

  <hr>

  <div style="background: black; color: white">black</div>
  <div style="background: var(--grey-0); color: white">grey-0</div>
  <div style="background: var(--grey-1); color: white">grey-1</div>
  <div style="background: var(--grey-2); color: white">grey-2</div>
  <div style="background: var(--grey-3); color: white">grey-3</div>
  <div style="background: var(--grey-4)">grey-4</div>
  <div style="background: var(--grey-5)">grey-5</div>
  <div style="background: var(--grey-6)">grey-6</div>
  <div style="background: var(--grey-7)">grey-7</div>
  <div style="background: white">white</div>
</fieldset>

### Layouts

<fieldset id="layout-stack">
  <legend>Stack</legend>

  <div class="layout stack">
    <header>
      <div class="brand">Header</div>
    </header>
    <nav>
      <ul>
        <li>Nav</li>
      </ul>
    </nav>
    <main>
      <h1>Main</h1>
    </main>
    <footer>
      &copy; 2019 Footer
    </footer>
  </div>
</fieldset>

<fieldset id="layout-one-two-one">
  <legend>One-Two-One</legend>

  <div class="layout one-two-one">
    <header>
      <div class="brand">Header</div>
    </header>
    <nav>
      <ul>
        <li>Nav</li>
      </ul>
    </nav>
    <main>
      <h1>Main</h1>
    </main>
    <footer>
      &copy; 2019 Footer
    </footer>
  </div>
</fieldset>

<fieldset id="layout-one-two-one-responsive">
  <legend>One-Two-One-Responsive</legend>

  <div class="layout one-two-one-responsive">
    <header>
      <div class="brand">Header</div>
    </header>
    <nav>
      <ul>
        <li>Nav</li>
      </ul>
    </nav>
    <main>
      <h1>Main</h1>
    </main>
    <footer>
      &copy; 2019 Footer
    </footer>
  </div>
</fieldset>
