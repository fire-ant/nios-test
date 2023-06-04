

# docker_build('nios-test-container',
#             context='./nios-test-container',
#             dockerfile='./nios-test-container/Dockerfile',
# )
k8s_yaml(helm('./charts/nios-test'))

k8s_resource(
   workload='chart-nios-test',
   port_forwards='8443:443'
)