<template>
    <div class="home">
        <!-- Hero Section -->
        <section>
            <br>
            <div class="about">
                <div class="container">
                    <br>
                    <!-- <div class="row align-items-center">
                        <div class="col-lg-12">
                            <div class="section-header text-center" style="margin-top: -20px;">
                                <p id="ad_title" class="inline-block mt-1 text-2xl font-bold tracking-wider 
                                bg-gradient-to-b from-green-900 to-gray-800 bg-clip-text text-transparent">
                                    About System
                                </p>
                            </div>
                        </div>
                    </div> -->
                    <div class="row align-items-center">
                        
                        <div class="col-lg-6">
                            <div class="content-box">
                                <h2>Predictive Maintenance Using IoT and Machine Learning in the Milk Industry</h2>
                                <p>
                                    The milk industry relies on efficient equipment such as pasteurizers, coolers, and storage tanks. 
                                    Regular maintenance is crucial to prevent equipment failures that can lead to spoilage and financial loss. 
                                    This system integrates IoT and AI to predict maintenance needs, ensuring smooth operations and reducing downtime.
                                </p>

                                <h3>Key Features</h3>
                                <ul>
                                    <li><strong>Real-time Monitoring:</strong> IoT sensors track temperature, pressure, and equipment performance.</li>
                                    <li><strong>Predictive Analytics:</strong> AI algorithms analyze collected data to anticipate potential failures.</li>
                                    <li><strong>Cloud-Based Data Storage:</strong> Enables secure storage, remote monitoring, and efficient data processing.</li>
                                    <li><strong>Mobile & Web Application:</strong> Interactive dashboards provide alerts and equipment status updates.</li>
                                    <li><strong>Cost Efficiency:</strong> Reduces maintenance costs and prevents product spoilage.</li>
                                </ul>

                                <h3>How It Works</h3>
                                <ol>
                                    <li><strong>Data Collection:</strong> IoT sensors capture key performance indicators such as temperature fluctuations and machine vibrations.</li>
                                    <li><strong>Data Transmission:</strong> The collected data is securely transmitted to the cloud for real-time analysis.</li>
                                    <li><strong>AI Analysis:</strong> Machine learning models detect patterns and predict maintenance requirements.</li>
                                    <li><strong>Alerts & Recommendations:</strong> Users receive notifications and suggested actions to prevent failures.</li>
                                </ol>

                                <h3>Target Users</h3>
                                <ul>
                                    <li>Dairy farmers and milk processing plants</li>
                                    <li>Milk transportation and logistics companies</li>
                                    <li>Equipment manufacturers and maintenance providers</li>
                                </ul>

                                <h3>Technologies Used</h3>
                                <h4>IoT Sensors:</h4>
                                <ul>
                                    <li>Temperature and humidity sensors</li>
                                    <li>Vibration and pressure sensors</li>
                                    <li>Flow meters for milk processing</li>
                                </ul>

                                <h4>AI Models Implemented:</h4>
                                <ul>
                                    <li>Neural Networks for predictive maintenance</li>
                                </ul>

                                <h4>Cloud Technologies:</h4>
                                <ul>
                                    <li>AWS IoT Core / Google Cloud IoT</li>
                                    <li>Firebase for real-time data access</li>
                                </ul>

                                <h4>User Interface:</h4>
                                <ul>
                                    <li>Web-based dashboard (VueJS, Flask, Laravel)</li>
                                </ul>

                                <h3>Expected Impact</h3>
                                <ul>
                                    <li>Increased efficiency and reduced downtime in milk processing plants.</li>
                                    <li>Minimized losses due to equipment failures and spoilage.</li>
                                    <li>Enhanced quality control and sustainability in dairy operations.</li>
                                </ul>

                                <br>
                                <p class="text-center">---- End ----</p>
                            </div>
                        </div>
                        <div class="col-lg-6">
                            <div class="about-img">
                                <img src="../../assets/Homepage_images/sobre.jpg" alt="Image" class="p-6">
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
    </div>
</template>

<script>
export default {
    name: 'HomeView',
};
</script>

<style scoped>
.content-box {
    max-height: 600px;
    overflow-y: auto;
    padding: 20px;
    background-color: white;
    border-radius: 10px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

h2, h3, h4 {
    font-family: sans-serif;
    font-weight: bold;
}

#ad_title {
    position: relative;
    display: inline-block;
}

#ad_title::after {
    content: '';
    position: absolute;
    bottom: 0;
    left: 50%;
    transform: translateX(-50%);
    width: 50%;
    height: 2px;
    background-color: black;
}
</style>
