<template>
    <div>
        <sidebar>
            <ul>
                <li>Stamp Duty</li>
                <li>Real Property Gains Tax</li>
                <ul>Rates</li>
                <ul>Premium</li>
                <ul>Development Charge</li>
                <ul>Quit Rent</ul>
                <ul>Estate Duty</ul>
                <ul>Income Tax</ul>
            </ul>
        </sidebar>
        <div id="landing">
            <div class="grid grid-cols-3">
                <Item
                    v-for=""
                    :key=""
                    :value=""
                />
            </div>
        </div>
    </div>
</template>
