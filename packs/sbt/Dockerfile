FROM dapengsoa/dapeng-container:2.1.2-SNAPSHOT
RUN ["mkdir", "-p", "\/dapeng-container"]
RUN ["mkdir", "-p", "\/apps\/purchase-scheduler_service"]
RUN ["chmod", "+x", "\/dapeng-container\/bin\/startup.sh"]
WORKDIR /dapeng-container/bin
COPY */*.jar /dapeng-container/apps/purchase-scheduler_service/
ENTRYPOINT ["\/dapeng-container\/bin\/startup.sh"]
