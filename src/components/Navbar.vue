<template>
  <nav class="navbar">
    <a>
        <svg width="19" height="14" viewBox="0 0 19 14" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path fill-rule="evenodd" clip-rule="evenodd" d="M0 1C0 0.447715 0.447715 0 1 0H18C18.5523 0 19 0.447715 19 1C19 1.55228 18.5523 2 18 2H1C0.447715 2 0 1.55228 0 1ZM0 7C0 6.44772 0.447715 6 1 6H18C18.5523 6 19 6.44772 19 7C19 7.55228 18.5523 8 18 8H1C0.447715 8 0 7.55228 0 7ZM1 12C0.447715 12 0 12.4477 0 13C0 13.5523 0.447715 14 1 14H18C18.5523 14 19 13.5523 19 13C19 12.4477 18.5523 12 18 12H1Z" fill="#617083"/>
        </svg>
    </a>
    <div class="profile">
        <img class="avatar"  src="../assets/avatar.jpeg">
        <a>Имя Пользователя</a>
        <a>
            <svg width="10" height="7" viewBox="0 0 10 7" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path fill-rule="evenodd" clip-rule="evenodd" d="M5 7L10 0H0L5 7Z" fill="#3E4956"/>
            </svg>
        </a>
    </div>
  </nav>
</template>

<script>
export default {
  name: 'Navbar'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  nav {
    position: fixed;
    width: calc(100% - 1rem);
    display: flex;
    background: #FFFFFF;
    border-bottom: 1px solid #DEE5EF;
    padding: 0.4rem 0.5rem;
    justify-content: space-between;
    height: 2rem;
  }
  .profile {
    display: flex;
    border-left: 1px solid #C4CFDD;
  }
  .avatar {
    padding: 0 0.5rem;
    border-radius: 50%;
    height: 2rem;
    width: 2rem;
    object-fit: cover;
  }
  .navbar a {
    padding: 0 0.5rem;
    font-size: 14px;
    color: #2B343F;
    font-weight: bold;
    font-size: 14px;
    line-height: 16px;
    margin-top: 0.6rem;
  }
</style>
