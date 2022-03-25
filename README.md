***************************************************#### Graph QL ####********************************************ABCDDDDD
second commit

feature commit
feature 2ndcommit

1. Query to fetch the data and Mutation to alter the data.

2. For fetching the data we use Graph QL Query
   To make it possible in java we use GraphQLQueryResolver Interface.

3. For altering the data i.e Create, Update and Delete we use GraphQL Mutation.
   We use GraphQLMutationResolver Interface.

4. Schema provides flexibility to consumers that which attributes they want in response. It has .graphqls file extension.


GraphQL Dependency

        <dependency>
			<groupId>com.graphql-java</groupId>
			<artifactId>graphql-java-tools</artifactId>
			<version>5.2.4</version>
		</dependency>

		<dependency>
			<groupId>com.graphql-java</groupId>
			<artifactId>graphql-spring-boot-starter</artifactId>
			<version>5.0.2</version>
		</dependency>

		<dependency>
			<groupId>com.graphql-java</groupId>
			<artifactId>graphiql-spring-boot-starter</artifactId>
			<version>5.0.2</version>
		</dependency>
