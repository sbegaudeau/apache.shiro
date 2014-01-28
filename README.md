Apache Shiro update site for Eclipse

Publication of the update site:
java -jar .\plugins\org.eclipse.equinox.launcher_1.3.0.v20130327-1440.jar -application org.eclipse.equinox.p2.publisher.FeaturesAndBundlesPublisher -metadataRepository file:/"output" -artifactRepository file:/"output" -source "input"/apache.shiro -configs ANY.ANY.ANT -compress -publishArtifacts


.\eclipse.exe -debug -consolelog -nosplash -verbose -application org.eclipse.equinox.p2.publisher.CategoryPublisher -metadataRepository
file:/"output" -categoryDefinition file:/"input"/apache.shiro/category.xml