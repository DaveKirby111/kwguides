<script>
  import { pageTitle } from "$lib/stores.js";
  $pageTitle = "dragon age II";
  import Sections from "$lib/sections.svelte";

  const sections = [
    {
      name: "guides",
      link: "#guides",
    },
  ];
</script>

<Sections {sections} />

<div id="guides" class="guides">
  <h2>guides</h2>

  <ul class="skip">
    <p class="fw-bold text-decoration-underline">Sections</p>
    <li><a href="#companions">companions</a></li>
  </ul>

  <div class="companions" id="companions">
    <h3>companions</h3>

    <div class="d-flex">
      <div class="aveline">
        <h4>aveline</h4>

        <h5>armor</h5>
        <ul>
          <li>Underpadding - Act 1, armor merchant in lowtown</li>
          <li>Flex Chain - Act 2, Raiders of the Cliffs quest</li>
          <li>Impact Plating - Act 2, armor merchant in lowtown</li>
          <li>
            Deflecting Joints - Act 3, Jeven's corpse during Favor and Fault
            quest
          </li>
        </ul>

        <h5>gift</h5>
        <p>
          Shield of the Knight Herself - Sir Varnell's Refuge, Offered and Lost
          quest
        </p>
      </div>

      <div class="fenris">
        <h4>fenris</h4>

        <h5>armor</h5>
        <ul>
          <li>Tevinter Spirit Symbol - Act 2, Robes by Jean Luc in hightown</li>
          <li>Lyrium Scales - Act 2, Shady Merchandise docks</li>
          <li>Reinforced Straps - Act 2, A Bitter Pill quest</li>
          <li>Enchanted Resin - Act 3, Mine Massacre quest</li>
        </ul>

        <h5>gifts</h5>
        <p>Blade of Mercy - Best Served Cold quest</p>
        <p>Book of Shartan - Act, alienage at night</p>
      </div>

      <div class="varric">
        <h4>varric</h4>

        <h5>armor</h5>
        <ul>
          <li>Inscribed Leather Harness - Act 1, apprel shop in lowtown</li>
          <li>
            Coat Lining with Concealed Pockets - Act 2, shady merchandise at
            docks
          </li>
          <li>Silverite Reinforced Buckles - Act 2, Family Matter quest</li>
          <li>Drakeskin Leg Straps - Act 3, Finding Nathaniel quest</li>
        </ul>

        <h5>gift</h5>
        <p>Signet Ring - Trinkets Emporium</p>
      </div>
    </div>

    <div class="d-flex">
      <div class="merrill">
        <h4>Merrill</h4>

        <h5>armor</h5>
        <ul>
          <li>Samite Lining - Act 2, Robes by Jean Luc in hightown</li>
          <li>
            Carved Ironwood Buttons, Act 2, Master Ilen's Shop in Sundermount
          </li>
          <li>
            Silver Threaded Dalish Embroidery - Act 2, Sundermount's mountain
            graveyard
          </li>
          <li>Halla Horn Buckles - Act 3, A New Path quest</li>
        </ul>

        <h5>gifts</h5>
        <p>Halla Carving - Act 2, Master Ilen's Shop</p>
        <p>Sylvanwood Ring - Act 3, Thief leader's body in Sundermount</p>
      </div>

      <div class="bethany">
        <h4>bethany</h4>

        <h5>armor</h5>
        <ul>
          <li>Heirloom Amell Protective Sigils - Act 1, Birthright quest</li>
        </ul>

        <h5>expedition</h5>
        <p>
          If left home - is taken to join the circle. Becomes a senior member of
          the circle and is happy where she is.
        </p>
        <p>
          If taken - dies or joins Grey Wardens. Is resentful at first but comes
          to accept her fate.
        </p>
      </div>

      <div class="carver">
        <h4>carver</h4>

        <h5>armor</h5>
        <ul>
          <li>Fereldan Girded Plating - Act 1, Birthright quest</li>
        </ul>

        <h5>expedition</h5>
        <p>If left home - joins templars.</p>
        <p>If taken - dies or joins Grey Wardens. Content with his fate.</p>
      </div>
    </div>
  </div>
  <a href="#top" class="skiplink">Top</a>
</div>

<style>
  h3 {
    font-size: 40px;
    text-align: center;
  }

  .aveline,
  .fenris,
  .varric,
  .merrill,
  .bethany,
  .carver {
    width: 33.3%;
    padding: 30px;
  }

  @media screen and (max-width: 600px) {
    .aveline,
    .fenris,
    .varric,
    .merrill,
    .bethany,
    .carver {
      width: 100%;
      padding: 0;
    }
  }
</style>
