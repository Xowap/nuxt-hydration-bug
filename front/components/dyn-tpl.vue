<script>
export default {
    props: {
        html: {
            type: String,
            required: true,
        },
    },

    render() {
        return h({
            template: this.html,
        });
    },
};
</script>
