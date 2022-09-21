Number of Islands

![image](https://user-images.githubusercontent.com/64318469/187841735-e15f5ce0-7b10-4a49-b814-168966b452c2.png)

Maximum Area of Island

![image](https://user-images.githubusercontent.com/64318469/187901665-0c6f471d-1c6d-4b99-ad78-592ef4d55df2.png)



Rotting tomatoes

    class Solution {
    public:
    int orangesRotting(vector<vector<int>>& grid) {
        int fresh=0;
        int time=0;
        queue<pair<int,int>>q;
        for(int i=0;i<grid.size();i++){
            for(int j=0;j<grid[0].size();j++)
            {
                if(grid[i][j]==1)
                    fresh++;
                if(grid[i][j]==2)
                    q.push(make_pair(i,j));
                
            }
         }
         while(q.size()>0 && fresh>0)
         {
             int l=q.size();
             for(int i=0;i<l;i++)
             {
                 
                 int m=q.front().first;
                 int n=q.front().second;
                 q.pop();
                 
                 if(m-1>=0){
                 if(grid[m-1][n]==1){
                     grid[m-1][n]=2;
                     q.push(make_pair(m-1,n));
                     fresh--;                 
                 }
                 }
                 if(m+1<grid.size()){
                 if(grid[m+1][n]==1){
                     grid[m+1][n]=2;
                     q.push(make_pair(m+1,n));
                     fresh--;                 
                 }
                 }
                 if(n-1>=0){
                 if(grid[m][n-1]==1){
                     grid[m][n-1]=2;
                     q.push(make_pair(m,n-1));
                     fresh--;                 
                 }
                 }
                 if(n+1<grid[0].size()){
                 if(grid[m][n+1]==1){
                     grid[m][n+1]=2;
                     q.push(make_pair(m,n+1));
                     fresh--;                 
                 }  
                 }                             
            }                  
            time++;
         }
        return (fresh==0)?time:-1;
        
        
    }
    };

Reverse Thinking : Capture Everything except the surrounding regions






Redundant Connection : Union Find Algorithm 











