<script>
    
    import { pageTitle } from "$lib/stores.js";
    pageTitle.set("Silent Hill 2 Remake");
    import Sections from "$lib/sections.svelte";

  //   const sections = [
  //   {
  //     name: "guides",
  //     link: "#guides",
  //   },
  // ];
  

  </script>
  
  <!-- <Sections {sections} /> -->

  <div id="guides" class="guides">

    <h2>guides</h2>

    <div class="guide-sections">
        <p class="fw-bold text-decoration-underline">Sections</p>
        <ul class="skip">
          <li><a href="#tombs">puzzles</a></li>
        </ul>
      </div>

      <div>
        <h3>puzzles</h3>

        <div>
          <p>Neely's Bar - Jukebox</p>
          <ol>
            <li>Half of broke vynl record and glue in Groovy Music shop.</li>
            <li>Register in Texan Cafe - turn key and press bottom right button for coin.</li>
            <li>No. 2 key in Saul apartments.</li>
            <li>Other half of record in Neely's bar.</li>
          </ol>
        </div>
      </div>

      <div>
        <p>Grand Market code</p>
        <p>Difficulty:</p>
        <ul>
          <li>Light: 4442</li>
          <li>Standard: 4444</li>
          <li>Hard: 4446</li>
        </ul>
      </div>

      <div>
        <p>Woodside Apartments - safe code</p>
        <p>Difficulty:</p>
        <ul>
          <li>Light: 15-11-13</li>
          <li>Standard and Hard: 13-7-11</li>
        </ul>
      </div>

      <div>
        <p>Woodside Apartments - Coin Puzzle</p>
        <p>Difficulty:</p>
        <table>
          <tr>
            <td>Light:</td>
            <td>
              <p>Man - O - Woman - O - Flower</p>
              <p>Sword - O - Woman - O - Snake</p>
              <p>Snake - O - Grave - O - Man</p>
              <p>Put any coin in top slot.</p>
            </td>
          </tr>
           <tr>
            <td>Standard:</td>
            <td>
              <p>Man - O - Woman - O - Flower</p>
              <p>O - Sword - O - Woman - Flower</p>
              <p>O - O - Man - Grave - Snake</p>
              <p>Put any coin in top slot.</p>
            </td>
          </tr>
           <tr>
            <td>Hard:</td>
            <td>
              <p>Man - O - O - Grave - Snake</p>
              <p>Grave - Sword - Flower - O - O</p>
              <p>O - Man - woman - O - Snake</p>
              <p>Put any coin in top slot.</p>
            </td>
          </tr>
        </table>
      </div>

      <div>
        <p>Blue Creek Apartments - Clock</p>
        <ul>
          <li>Hour: 9</li>
          <li>Minute: 2</li>
          <li>Second: 3</li>
        </ul>
      </div>

      <div>
        <p>Blue Creek Apartments - Moth Puzzle</p>
        <p>Difficulty:</p>
        <ul>
          <li>Light: 5-8-2</li>
          <li>Standard: 3-7-3</li>
          <li>Hard: 5-2-2</li>
        </ul>
      </div>

      <div>
        <p>Jack's Inn Safe</p>
        <p>Difficulty:</p>
        <ul>
          <li>Light and Standard: 0451</li>
          <li>Hard: 0533</li>
        </ul>
      </div>

      <div>
        <p>Bowling Alley safe - New Game Plus ONLY</p>
        <p>All difficulties: 1887</p>
      </div>

      <div>
        <p>Hospital padlock - 1F</p>
        <p>Difficulty:</p>
        <ul>
          <li>Light: 2-8-7</li>
          <li>Standard: 7-2-4</li>
          <li>Hard: 1-5-2</li>
        </ul>
      </div>

      <div>
        <p>Nurses Station Keypad</p>
        <p>Difficulty:</p>
        <ul>
          <li>Light and Standard: 3587</li>
          <li>Hard: 7456</li>
        </ul>
      </div>

      <div>
        <p>Hospital door code - 3F</p>
        <p>All difficulties: 4-37-12</p>
      </div>

      <div>
        <p>Hospital Bracelet Puzzle</p>
        <p>92-45-71</p>
      </div>

      <div>
        <p>Hospital Elevator Quiz</p>
        <p>2-3-1</p>
      </div>

      <div>
        <p>Hospital-chained box</p>
        <p>Keypad: 9659</p>
        <p>Lock: 1622</p>
      </div>

      <div>
        <p>Historical society - bug room</p>
        <p>The combination will be random each playthrough - but will always contain 2,3, and 9.</p>
        <p>Combinations:</p>
        <ol>
          <li>2-3-9</li>
          <li>2-9-3</li>
          <li>3-2-9</li>
          <li>3-9-2</li>
          <li>9-2-3</li>
          <li>9-3-2</li>
        </ol>
      </div>

      <div>
        <p>Hotel - Music Box</p>
        <p>Have to turn the figurines.</p>
        <p>Difficulty:</p>
        <ul>
          <li>Light: 7-2-1</li>
          <li>Standard: 7-5-1</li>
          <li>Hard: 1-1-1</li>
        </ul>
      </div>

      <div>
        <p>Hotel - Book Puzzle</p>
        <ul>
          <li>Upper Left: Winged Man</li>
          <li>Lower Left: Bull</li>
          <li>Upper Right: Eagle</li>
          <li>Lower Right: Lion</li>
        </ul>
      </div>

      <div>
        <p>Hotel - Suitcase Code</p>
        <p>Difficulty:</p>
        <ul>
          <li>Light: Dark Wish</li>
          <li>Standard: Deed Done</li>
          <li>Hard: Love Lust</li>
        </ul>
      </div>

      <div>
        <p>Hotel - Employee Section Safe</p>
        <p>All difficulties: 7414</p>
      </div>


      <a href="#top" class="skiplink">Top</a>
  </div>
  
  
  
  <style>

    table, td {
      border: 1px solid black;
      border-collapse: collapse;
      padding: 20px;
    }

    ul li {
      list-style-type: none;
    }
    
  </style>
  