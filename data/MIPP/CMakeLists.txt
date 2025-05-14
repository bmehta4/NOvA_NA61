
install( FILES
           MIPPNuMI_MC_K0L.xml
           MIPPNuMI_MC_K0S.xml
           MIPPNuMI_MC_KAM.xml
           MIPPNuMI_MC_KAP.xml
           MIPPNuMI_MC_PIM.xml
           MIPPNuMI_MC_PIP.xml
         DESTINATION data/MIPP )

install( FILES
           fK_mipp_replica.root
           fmc_tar.root
           fpi_mipp_replica.root
           tarpos_yield_le.root
           tarpos_yield_me.root
         DESTINATION data/MIPP )
