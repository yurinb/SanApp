<template>
  <transition name="modal">
    <div class="modal-mask">
      <div class="modal-wrapper">
        <div class="modal-container">

          <div class="modal-header">
            <slot name="header">
              default header
            </slot>
          </div>

          <div class="modal-body">
            <slot name="content">
              default body
            </slot>
          </div>

          <div class="modal-footer">
            <slot name="footer">
              btn 
            </slot>
          </div>

        </div>
      </div>
    </div>
  </transition>

</template>


<script>
export default {}
</script>
