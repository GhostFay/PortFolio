<template>

<div class="main-container">
    <h1>Test PortFolio</h1>
    <div class="container-one">
        <div class="profile">
            <img src="../assets/" alt="profile pic">
        <h3>Name Here</h3>
        <p>SoftWare Developper</p>
        </div>
            
    <div class="social-links">
      
            <div class="link">
             
               
                <a href="">    <img src="" alt="githublogo"><h2>GitHub</h2></a>
            </div>
            <div class="link">
               
                <a href="">   <img src="" alt="Linkedinlogo">  <h2>LinkedIn</h2></a>
            
            </div>
            <div class="link">
              
                <a href=""> 
                    <img src="" alt="twitterlogo">
                    <h2>Twitter</h2></a>
               
            </div>
            <div class="link">
                
              
                <a href="">  <img src="" alt="instalogo"><h2>Instagram</h2></a>
            </div>
      
    </div>
</div>
<div class="container-two">
    <div class="about-me">
        <h1>Lorem ipsum dolor sit amet consectetur adipisicing elit. Facilis veniam deserunt 
            hic molestiae unde sed aut esse rem voluptatum et quam natus officia repellendus, 
            doloremque magnam inventore eaque? Sed, fugit?</h1>
    </div>

    <div class="technology-section">
        <h1>Technologies Studied</h1>
        <div class="logo">
            <img src="" alt="javascript">
            <img src="" alt="html">
            <img src="" alt="css">
        </div>
        <div class="button-container">
            <div class="projects-button">
                <a href="">My Projects</a>
            </div>
            <div>
                <a href="">My resume</a>
            </div>
        </div>
    </div>

</div>
</div>

</template>

<script>
export default {

}

</script>
<style scoped>
img{
    height: 20px;
}
.main-container {
    display: flex;
    flex-direction: row;
    background-color: #cecece;

}

.conainer-one{
    background-color: #ffb0b0;
    padding: 2.5%;
    width: 30%;
}

.conainer-two{
    background-color: #cdc0fc;
    width: 70%;
}

.profile img {
    height: 5rem;
    border-radius: 50%;
}

.link a{
 text-decoration: none;
 color: #2c3e58;
 font-size: 10px;
}

</style>