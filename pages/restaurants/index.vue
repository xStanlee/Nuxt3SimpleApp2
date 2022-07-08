<template>
    <div>
        <Html lang="en-US">
            <Head>
            <Title>Top 50 restaurants</Title>
            <Meta 
            name="description"
            content="Learn the stuff"/>
            <Link rel="preload" href="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQqfKhQ5AI4L3u9sJr7QRZUpOIcyS4Ok2kAmQ&usqp=CAU" as="script" />
            </Head>
        </Html>
        <NuxtLayout name="custom">
            <div class="container">
                <RestaurantTable />
            </div>
        </NuxtLayout>
    </div>
</template>