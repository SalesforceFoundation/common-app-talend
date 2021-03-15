# Use Talend to Import Common App Data into Salesforce

If you’re a Common App member school looking to import applicant data into Education Data Architecture (EDA) and you’d like to use Talend as your ETL tool, use these sample jobs to help you implement your own integration. The provided Talend jobs import Common App applicant data and PDF documents into Salesforce staging records. After the staging records are created, you can run a batch job provided in the Education Cloud Integration with Common App package to move the data and PDFs from staging records to EDA records. 

For documentation about what the Talend jobs do and how to configure the jobs for your institution, see [Sample Talend Jobs for the Education Cloud Integration with Common App Package](https://sfdo-docs.s3-us-west-2.amazonaws.com/Integrate_Common_App_with_EDA_Talend_Jobs.pdf).

For details about the Education Cloud Integration with Common App package, see [Import Common App Data and Documents into EDA](https://powerofus.force.com/s/article/EDA-Integrate-Common-App).

**IMPORTANT**: These Talend jobs are provided as *samples* only. They provide an example of how an ETL tool can be used to import Common App data and stage it in Salesforce. These jobs are *not* an official solution, are not endorsed by Salesforce and they are *not* officially supported. The documentation assumes you’re familiar with Talend, have access to install or upgrade Java on your computer, and have support resources to assist you in any troubleshooting efforts encountered as part of this setup.
