<template>
    <div>
        <slot name="header" />
         <div>
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQqfKhQ5AI4L3u9sJr7QRZUpOIcyS4Ok2kAmQ&usqp=CAU" alt="Sadface ;(">
        </div>
        <slot name="redirect" />
    </div>
</template>

<style scoped>
img {
  width: 10rem;
  height: 10rem;
  margin: 3rem 0;
}
</style>