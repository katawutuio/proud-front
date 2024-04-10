<template>
        <v-container
        class="mb-6"
        >
        <v-row
            align="start"
            no-gutters
        >
            <v-col cols="12">
                <div>
                <v-label class="font-weight-medium mb-2">ID</v-label>
                    <v-text-field
                        label="id"
                    >
                    </v-text-field>
                </div>

                <div>
                <v-label class="font-weight-medium mb-2">Name</v-label>
                    <v-text-field
                        label="name"
                    >
                    </v-text-field>
                </div>

                <div>
                <v-label class="font-weight-medium mb-2">Surname</v-label>
                    <v-text-field
                        label="surname"
                    >
                    </v-text-field>
                </div>
            </v-col>
            <v-col cols="12" class="d-flex justify-end pt-6 mt-6">
                <v-btn @click="$router.go(-1)" color="secondary" variant="outlined" class="mr-2">Cancel</v-btn>
                <v-btn @click="" color="secondary" flat>Save</v-btn>
            </v-col>
        </v-row>
        </v-container>
</template>