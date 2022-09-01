<template>
    <div>
        <sidebar>
            <ul>
                <li>Stamp Duty</li>
                <li>Real Property Gains Tax</li>
                <li>Rates</li>
                <li>Premium</li>
                <li>Development Charge</li>
                <li>Quit Rent</li>
                <li>Estate Duty</li>
                <li>Income Tax</li>
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
