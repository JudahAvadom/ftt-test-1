<template>
    <div class="events">
        <div class="cards">
            <div class="card">
                <h3>Event 1</h3>
                <label>Lorem ipsum dolor sit amet consectetur adipisicing elit. Obcaecati porro delectus alias doloremque rem necessitatibus fugit quae hic nesciunt deleniti. Fugiat cupiditate soluta quidem amet, eligendi quaerat quis exercitationem vel similique provident ratione nihil hic ducimus, pariatur earum suscipit cum? Mollitia ullam laudantium quia autem rem debitis? Non delectus cum accusamus provident consectetur molestiae est, sint quibusdam voluptate rem alias aliquid itaque saepe nesciunt aperiam odio sapiente ratione ad ut corrupti officia fugiat? Dolorem inventore rerum doloribus est iure voluptatum, pariatur sed amet delectus possimus non iste veniam sint, facere nostrum illum ut id enim voluptate excepturi? Vel, accusamus possimus?</label>
            </div>
            <div class="card">
                <h3>Event 2</h3>
            </div>
            <div class="card">
                <h3>Event 3</h3>
            </div>
        </div>
    </div>
</template>

<style lang="scss">
    .events {
        padding: 0 9%;
        .cards {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(400px, 1fr));

            grid-auto-rows: auto;
            grid-gap: 1rem;

            .card {
                border: 2px solid #e7e7e7;
                border-radius: 4px;
                padding: .5rem;
                text-align: center;
            }
        }
    }
</style>

<script>
export default {
    name: "Events"
}
</script>