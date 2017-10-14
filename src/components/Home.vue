<template>
  <main>
    <toolbar />
    <my-header />
    <hello />
    <get-started />
    <connection />
    <my-footer />
  </main>
</template>
<script>
import Toolbar from './Toolbar'
import Header from './Header'
import Hello from './Hello'
import GetStarted from './GetStarted'
import Connection from './connection/Index'
import Footer from './Footer'
export default {
  components: {
    myHeader: Header,
    Hello,
    myFooter: Footer,
    Connection,
    GetStarted,
    Toolbar
  }
}
</script>
