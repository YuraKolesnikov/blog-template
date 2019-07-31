<template>
  <Container>
    <Row>
      <template v-for="input in formFields">
        <InputText :key="input.id" :input="input" />
        {{input.vModel}}
      </template>
    </Row>
  </Container>
</template>
<script>
import Container from '@/components/Container'
import Row from '@/components/Row'
import InputText from '@/components/atoms/InputText'
export default {
  components: {
    Container,
    Row,
    InputText
  },
  data() {
    return {
      formFields: [
        {
          id: "ling",
          placeholder: "Ling Ling",
          type: "text",
          required: true,
          vModel: ""
        },
        {
          id: "password",
          placeholder: "12345",
          type: "password",
          required: true,
          vModel: ""
        }
      ]
    }
  }
};
</script>