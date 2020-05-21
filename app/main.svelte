<script>
  const name = "world";
</script>

<main>
  <header>
    <nav>
      <a href="/"
        ><img
          alt="Logo"
          src="https://via.placeholder.com/200x70?text=Logo"
          height="70"
      /></a>
      <ul>
        <li>Menu Item 1</li>
        <li><a href="#">Menu Item 2</a></li>
        <li>
          <a href="#">Dropdown Menu Item</a>
          <ul>
            <li><a href="#">Sublink with a long name</a></li>
            <li><a href="#">Short sublink</a></li>
          </ul>
        </li>
      </ul>
    </nav>
  </header>
  <section>
    <header>
      <h2>Section Heading - Hello {name}!</h2>
      <p>Section Subheading</p>
    </header>
    <aside>
      <h3>Card heading</h3>
      <p>Card content*</p>
      <p><small>*with small content</small></p>
    </aside>
    <aside>
      <h3>Card heading</h3>
      <p>Card content <sup>with notification</sup></p>
    </aside>
    <aside>
      <h3>Card heading</h3>
      <p>Card content</p>
    </aside>
  </section>
  <div>
    <details>
      <summary>Expanable title</summary>
      <p>Revealed content</p>
    </details>
    <details>
      <summary>Another expanable title</summary>
      <p>More revealed content</p>
    </details>
    <br />
  </div>
  <footer>
    <small>Footer</small>
  </footer>
</main>
