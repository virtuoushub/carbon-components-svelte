<script>
  let className = undefined;
  export { className as class };
  export let style = undefined;

  import { cx } from '../../lib';
</script>

<div
  on:click
  on:mouseover
  on:mouseenter
  on:mouseleave
  class={cx('--form-item', '--checkbox-wrapper', '--checkbox-label', className)}
  {style}>
  <span class={cx('--checkbox-label-text', '--skeleton')} />
</div>
