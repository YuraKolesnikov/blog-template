<template>
  <div class="home">
    <Container>
      <Row>
        <div class="col-3"></div>
        <div class="col-3"></div>
        <div class="col-3"></div>
        <div class="col-3"></div>
      </Row>
      <Row>
        <div class="col-4"></div>
        <div class="col-4"></div>
        <div class="col-4"></div>
      </Row>
      <Row>
        <div class="col-6"></div>
        <div class="col-6"></div>
      </Row>
      <Row>
        <div class="col-12"></div>
      </Row>
    </Container>
  </div>
</template>
<script>
import Container from '@/components/Container'
import Row from '@/components/Row'
import FullWidthBox from '@/components/atoms/FullWidthBox'
export default {
  components: {
    Container,
    Row,
    FullWidthBox
  },
  data() {
    return {
      
    }
  }
}
</script>
