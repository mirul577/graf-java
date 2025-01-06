# graf-java
make graf in php
<script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <script>
        // Data for the chart
        const ctx = document.getElementById('dataChart').getContext('2d');
        const dataChart = new Chart(ctx, {
            type: 'line',
            data: {
                labels: ['X', 'Instagram', 'TikTok', 'Facebook', 'Reddit'],
                datasets: [{
                    label: 'Comment',
                    data: [21, 25, 26, 26, 36],
                    borderColor: 'rgba(75, 192, 192, 1)',
                    borderWidth: 2,
                    fill: false
                }]
            },
            options: {
                responsive: true,
                plugins: {
                    legend: {
                        display: true
                    }
                }
            }
        });
    </script>
