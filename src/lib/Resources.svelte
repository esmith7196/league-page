<script>
  import List, { Item, Graphic, Separator, Text } from '@smui/list';
  import { dynasty } from './utils/helper';

  const today = new Date();
  const resources = [];
</script>

<div class="pageBody">
  <div class="banner">
    <h4>Helpful Dynasty Resources</h4>
    <p>Cooming soon.</p>
  </div>
</div>

<style>
  .pageBody {
    position: relative;
    z-index: 1;
  }

  :global(.list) {
    width: 90%;
    max-width: 800px;
    border: 1px solid var(--mdc-theme-text-hint-on-background, var(--d7d7d7));
    margin: 15px auto;
    padding: 0 !important;
    box-shadow: 0px 3px 3px -2px var(--boxShadowOne),
      0px 3px 4px 0px var(--boxShadowTwo), 0px 1px 8px 0px var(--boxShadowThree);
  }

  :global(.linkText) {
    font-size: 1.1em;
  }

  a {
    color: var(--g555);
    font-size: 1.1em;
    text-decoration: none;
  }

  h4,
  p {
    text-align: center;
  }

  .disclaimer {
    color: #888;
    text-align: center;
  }
</style>
